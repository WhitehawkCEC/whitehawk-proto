# AGENTS.md

This file contains instructions and guidelines for AI agents working with this codebase.

## General Guidelines

- Always strive to write clean, maintainable, and well-documented code.
- Follow the existing coding style and conventions used in the project.
- Before submitting any changes, ensure that all tests pass and the code is properly formatted.
- If you encounter any issues or have questions, please ask for clarification.

## Project-Specific Instructions

- (Add any project-specific instructions here)

## Service Design

- Services should adhere to a resource-based naming scheme.
  Use a separate `service.proto` for each logical resource.

  The package

  `package whitehawk.proto.internal.client_portal.manufacturers__0__products.v1;`

  would represent the REST equivalent of `/manufacturers/{id}/products/`.

  For collection-based resources, stick to CRUDL (`Create`, `Read`, `Update`, `Delete`, `List`).

  ```proto
  service Service {
    rpc Create(CreateRequest) returns (CreateResponse);
    rpc Delete(DeleteRequest) returns (DeleteResponse);
    rpc Update(UpdateRequest) returns (UpdateResponse);
    rpc Read(ReadRequest) returns (ReadResponse);
    rpc List(ListRequest) returns (stream ListResponse);
  }
  ```

  For singleton resources, stick to `Get` and `Set`.

  ```proto
  service Service {
    rpc Get(GetRequest) returns (GetResponse);
    rpc Set(SetRequest) returns (SetResponse);
  }
  ```

- Explicitly mark all fields as `optional`.

- Always use `(google.api.field_behavior)` to mark application-level nullability.
  - `[(google.api.field_behavior) = REQUIRED]`
  - `[(google.api.field_behavior) = OPTIONAL]`
