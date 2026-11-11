# CI detection fixture

Java repo. Maven@3 with `goals: test` but `options: -DskipTests`. The skip flag rides the SECOND input - it must still win.

Expected verdict line in the Octiq chat:

    anything EXCEPT 'Tests required'
