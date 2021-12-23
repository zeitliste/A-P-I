# A-P-I

The API is a REST API that allows you to interact with a account programmatically. You can track time, and more.

Supported formats

We support JSON and XML to send and receive data.

List all time entries

GET /time_entries

Status: 200 OK

[
   {
      "time_entry": {...}
   },
   {
      "time_entry": {...}
   }
]


Retrieve a time entry

GET /time_entries/{TIME_ENTRY_ID}


Create a time entry via start and end time

POST /time_entries


Update a time entry

PATCH /time_entries/{TIME_ENTRY_ID}


Delete a time entry

DELETE /time_entries/{TIME_ENTRY_ID}


Restart a stopped time entry

PATCH /time_entries/{TIME_ENTRY_ID}/restart


Stop a running time entry

PATCH /time_entries/{TIME_ENTRY_ID}/stop
