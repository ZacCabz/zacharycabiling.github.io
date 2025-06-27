# Contact Information
> Email: ZacharyCabiling@gmail.com
>
> Phone Number: +1 (717) 686-5947

# **_Related Experience in Cybersecurity_**

## ANZ Australia Cyber Security Management Job Simulation on Forage January 2025
* Completed a simulation focussed on identifying cybersecurity threats at ANZ
* Investigated e-mails to report suspicious items
* Analysed a Packet Capture file using an open-source tool to identify and investigate any potential threats

## Datacom Cybersecurity Job Simulation on Forage January 2025
* Completed a simulation focussed on how Datacom's cybersecurity team helps protect its clients
* Investigated a cyberattack and produced a comprehensive report documenting findings
* Outlined key recommendations to improve a client's cybersecurity posture
* Conducted a comprehensive risk assessment

## Mastercard Cybersecurity virtual experience program on Forage January 2025
* Completed a job simulation where I served as an analyst on Mastercard’s Security Awareness Team
* Helped identify and report security threats such as phishing
* Analysed and identified which areas of the business needed more robust security training
* Implemented training courses and procedures for those teams

* * * 

# Projects
## C Programming Project - Boulder Break
Boulder break is a 2-dimensional puzzle game. Goal is to help an adventurer collect treasure. Escape from a cave by pushing boulders into holes that may block the exit

## Python Programming Project - NHL Goal Graphical Display
Application recreates a new and improved NHL statistics user face. Aims to give the user up-to-date information on NHL goals. Tool can track team dynamics by evaluating the scores of different NHL teams

* * * 
## Example Code from Python
```python
// Python code with syntax highlighting.
def load_teams_data_csv(file_path):
    try:
        teams_data = {}
        with open(file_path, 'r') as file:
            csvreader = csv.reader(file)
            for row in csvreader:
                # Get Team Name
                team_name = row[0]
                # Extract goals data for the periods and map them to the team
                goals_data = {
                    'Playoff Goals': int(row[3]) if row[3] else None,
                    '1st Period Goals': int(row[4]) if row[4] else None,
                    '2nd Period Goals': int(row[5]) if row[5] else None,
                    '3rd Period Goals': int(row[6]) if row[6] else None,
                }
                teams_data[team_name] = goals_data
        return teams_data
    except Exception as e:
        messagebox.showerror("Error", f"Failed to load CSV data: {e}")
        return {}
```

## Technical Skills
### Coding Languages
* Matlab, C, Python, SQL
  
### Developer Tools
* Github, VS Code, Wireshark, PuTTy, Nmap, Zenmap

### Libaries
* Tkinter
  
```
Thanks for reading my Cybersecurity Profile.
```
