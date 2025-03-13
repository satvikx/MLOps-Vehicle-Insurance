Create Virtual Env ```uv venv venv```
Activate (Git Bash) ```source venv/Scripts/activate``` or ```source activate```

To setup the connection url on mac(also work for windows), open bash/powershell terminal and run below command:
                        *** For Bash ***
    set: export MONGODB_URL="mongodb+srv://<username>:<password>......"
    check: echo $MONGODB_URL
                        *** For Powershell ***
    set: $env:MONGODB_URL = "mongodb+srv://<username>:<password>......"
    check: echo $env:MONGODB_URL

    To setup the connection url on Windows, open env variable setting option and add a new variable:
    Name: MONGODB_URL, Value = <url>