# MultiTrans API Documentation #
## MultiTrans RESTful Web Services ##
The MultiTrans REST API allows external systems to create translation projects programmatically in the MultiTrans TMS, to retrieve statuses of those projects and to retrieve the final translated documents. Various other information can also be retrieved or managed through the API, including retrieving and accepting quotes and retrieving or updating details on projects and tasks. The MultiTrans REST API is documented and can be tested through Swagger, directly on your MultiTrans server. 

## Technical Documentation ##
The technical documentation for the MultiTrans API is split into five sections:

### [Accessing Sample Code](https://docs.rws.com/785465/816309/sdl-multitrans/accessing-sample-code) ###
Swagger documentation is available to authenticated users, to provide sample code to assist in development.

### [Supported file types](https://docs.rws.com/785465/816340/sdl-multitrans/supported-file-types) ###
The REST API does not process the contents of files, so the only restrictions on file types are those blocklisted by the MultiTrans server. Because the file contents are not processed, the restrictions are based on the file extensions.

### [Available methods](https://docs.rws.com/785465/816345/sdl-multitrans/available-methods) ###
The available methods described here give an overview of the functionality available using the MultiTrans REST API. For the full details required for development, refer to your Swagger environment for sample code.

### [Uploading documents](https://docs.rws.com/785465/816946/sdl-multitrans/uploading-documents) ###
For any method in which documents are uploaded to MultiTrans, the documents can be uploaded using a URL, a file path or via Base64. When uploading documents using a URL or a file path, MultiTrans must have access to the URL or the path.

### [Mapping languages](https://docs.rws.com/785465/816953/sdl-multitrans/mapping-languages) ###
MultiTrans supports ISO 639-3 (example ENG, FRA) and RFC 3066 (example en-CA and de-CH) language codes. If the system connecting to the MultiTrans TMS uses language codes other than these, a map file must be configured and placed on the server to convert the language codes on demand.

Please visit **[MultiTrans technical documentation](https://docs.rws.com/785465/816303/sdl-multitrans/rest-api)** to learn more.
