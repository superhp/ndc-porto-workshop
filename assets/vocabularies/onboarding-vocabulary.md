## Onboarding API Vocavulary

### Actions

 * InitializeOnboarding
 * SaveCompany
 * SaveAccount
 * SaveActivity
 * CancelOnboarding
 * CompleteOnboarding

### Onboarding data

* activityId
* activityType (r)(e)
* companyId (r)
* accountId
* dataScheduled
* notes
* status (r)(e)
* dateCreated
* dateUpdated

Valid _activityType_ values are:
- email
- inperson
- phone
- letter

Valid _status_ values are:
 - suspended
 - pending
 - active
 - closed
