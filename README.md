# Quiz-Assess-Programmatic-c.16-l.1-

Gather

import pandas as pd
import zipfile

# Extract all contents from zip file
with zipfile.ZipFile('armenian-online-job-postings.zip', 'r') as myzip:
    myzip.extractall()

# Read CSV (comma-separated) file into DataFrame
df = pd.read_csv('online-job-postings.csv')

Assess

df

# Display the first five rows of the DataFrame using .head

# Display the last five rows of the DataFrame using .tail

# Display a basic summary of the DataFrame using .info

# Display the entry counts for the Year column using .value_counts

    Missing values (NaN)
    StartDate inconsistencies (ASAP)
    Nondescriptive column headers (ApplicationP, AboutC, RequiredQual ... and also JobRequirment)
    
