# phonebook

Your task is to write a phonebook application where users can either query for names or phone numbers.

The phonebook consists of the following entries:

- Alice, 0255334232
- Bob, 0434235235
- Franz, 095487963
- Else, 024654968

Every entry has a `name` and a `number`.

The user is able to pass the name or phone number they're looking for via the command line:

Look up the entry by its number:
```bash
$ ruby phonebook.rb 024654968
=> Else
```

Look up the entry by its name:
```bash
$ ruby phonebook.rb Else
=> 024654968
```

If the phonebook does not contain the requested entry, the following should happen:

```bash
$ ruby phonebook.rb Notthere
=> No entry 'Notthere' found
```
