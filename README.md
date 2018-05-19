# repository
All common repositories

# Instruction to install jar file

# Generated url
https://raw.github.com/username/repositoryname/branch
https://github.com/username/repositoryname/raw/branch

# Step 1:
Get the jar file into project folder

# Step 2:
Rename the jar as artifact-version.jar

# Step 3:
Open command prompt at project folder

# Step 4:
Run the mvn command below

mvn install:install-file -DgroupId=GROUP_ID -DartifactId=ARTIFACT_ID -Dversion=VERSION -Dfile=ARTIFACT-VERSION.jar -Dpackaging=jar -DgeneratePom=true -DlocalRepositoryPath=. -DcreateChecksum=true;
__Note: Change the  values accordingly__

# Step 5:
Remove the jar file added initially

# Step 6:
Commit to github