```bash
cmosjumper@github:~$ gh --help
Usage: gh [OPTION]... [ARGUMENT]...
Displays the information an user of 'https://github.com'.

If the user is angry, it does not show anything.
If the user is hungry, it displays '🍕'.

Options:
    -u, --username=USERNAME
            The username of the user you wish to view information about.
            Can be any username in GitHub (default 'me' if omitted).

    -i, --info=SECTION
            Section of the user information to be retrieved. Sections:
            personal, dev, contact.

    --all
            Displays all user information.

    If no --info or --all parameters are specified, --all is assumed.

cmosjumper@github:~$ gh --username='CMOSJumper' --info='personal'
+---------------+-------------------------------+
|   name        |   Jahns Saez                  |
+---------------+-------------------------------+
|   ocupation   |   Desarrollador Full Stack    |
+---------------+-------------------------------+

cmosjumper@github:~$ gh --info='dev'
No username specified, using 'me' instead (current user).

+-----------+---------------------------------------------------+
|   code    |   Javascript, TypeScript, C#, Python, HTML, CSS   |
+-----------+---------------------------------------------------+

+-------------------------------------------------------+
|                      technologies                     |
+---------------+---------------------------------------+
|   frontend    |   Next.js, React, Angular             |
+---------------+---------------------------------------+
|   lib         |   jQuery                              |
+---------------+---------------------------------------+
|   CSS         |   Bootstrap, Materialize              |
+---------------+---------------------------------------+
|   backend     |   Asp.Net Core, Django, Express       |
+---------------+---------------------------------------+
|   databases   |   MySQL, SQL Server, Oracle, SQLite   |
+---------------+---------------------------------------+

cmosjumper@github:~$ gh --username='CMOSJumper' --info='contact'
No username specified, using 'me' instead (current user).

+---------------------------+
|          contact          |
+---------------+-----------+
|   linkedin    |   empty   |
+---------------+-----------+
|   instagram   |   empty   |
+---------------+-----------+
|   website     |   empty   |
+---------------+-----------+
```

<!---
CMOSJumper/CMOSJumper is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
