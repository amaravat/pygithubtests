# pygithubtests
This is an automation test script using github apis

Run the script as :
python creat_user.py --invite -u username -e email-id
   This will invite the username provided as argument to your organization if the user has an Github account. If it could not find the user name, it exits with "user not found"

python create_user.py --remove -u username -e email-id
   This will do the exactly the samething as above , but here it removes the given userid  as a member from your organization.

python create_user.py --getmembers -u username -e email-id
   This will get all the active members in your organization and all the repos in your organization and saves this info in a file local to the script.

Confluence Intergration to this script is pending as this helps us to save the information to confluecne instead of having local files.


