---
swagger: "2.0"
x-collection-name: GoToMeeting
x-complete: 0
info:
  title: Go To Webinar Get session questions
  description: Retrieve questions and answers for a past webinar session. For technical
    reasons, this call cannot be executed from this documentation. Please use the
    curl command to execute it.
  termsOfService: https://developer.citrixonline.com/terms-use
  contact:
    name: Developer Support
    url: https://developer.citrixonline.com
    email: developer-support@citrixonline.com
  version: 1.0.0
host: api.citrixonline.com
basePath: /G2W/rest
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /organizers/{organizerKey}/webinars/{webinarKey}/sessions/{sessionKey}/attendees/{registrantKey}/questions:
    get:
      summary: Get attendee questions
      description: Get questions asked by an attendee during a webinar session. For
        technical reasons, this call cannot be executed from this documentation. Please
        use the curl command to execute it.
      operationId: getAttendeeQuestions
      x-api-path-slug: organizersorganizerkeywebinarswebinarkeysessionssessionkeyattendeesregistrantkeyquestions-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Organizers
      - OrganizerKey
      - Webinars
      - WebinarKey
      - Sessions
      - SessionKey
      - Attendees
      - RegistrantKey
      - Questions
  /organizers/{organizerKey}/webinars/{webinarKey}/sessions/{sessionKey}/questions:
    get:
      summary: Get session questions
      description: Retrieve questions and answers for a past webinar session. For
        technical reasons, this call cannot be executed from this documentation. Please
        use the curl command to execute it.
      operationId: getQuestions
      x-api-path-slug: organizersorganizerkeywebinarswebinarkeysessionssessionkeyquestions-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Organizers
      - OrganizerKey
      - Webinars
      - WebinarKey
      - Sessions
      - SessionKey
      - Questions
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---