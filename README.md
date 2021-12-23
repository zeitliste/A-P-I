# A-P-I

Our API is designed around the principles of REST.

Supported formats

We support JSON and XML to send and receive data.

List all time entries

GET /time_entries.json

Status: 200 OK

[
   {
      "time_entry": {...}
   },
   {
      "time_entry": {...}
   }
]
