### Doctrine 

#### migrate down or revert a migration 

**print migrations status**

` doctrine: migrations: status `

take the number in “Current Version” (format YYYYMMDDHHMMSS) and then run

` doctrine: migrations: execute YYYYMMDDHHMMSS --down `
