This folder contains several scripts each with a different shell permissions

- `0-iam_betty`: This script switches the current user to a user `betty`.
- `1-who_am_i`: This script prints the effective username of the current user.
- `4-empty`: This script creates an empty file called `hello`.
- `5-execute`: This script adds execute permissions to the owner of the file `hello`.
- `6-multiple_permissions`: This script adds execute permissions to the owner and the group owner, and read permissions to other users of the file `hello`.
- `9-John_Doe`: This script sets the mode of the file `hello` to `-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello`.

