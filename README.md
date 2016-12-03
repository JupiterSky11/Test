#This is Python.  Paste into Python to run.
hello = "Hello world - this is JupiterSky, your creator. "
forever = "true"
ticks = 0
seconds = 0
minutes = 0

while forever == "true":
    ticks = ticks + 1
    if ticks >= 50000:
        seconds = seconds + 1
        ticks = ticks - ticks
    if seconds >= 60:
        minutes = minutes + 1
        seconds = seconds - seconds
    print("Ticks: ",ticks," Seconds: ",seconds," Minuets: ",minutes)
