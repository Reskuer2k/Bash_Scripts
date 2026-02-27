# Bash_Scripts
10 Bash Scripts Every Linux SysAdmin Should Have Ready
How to Use These Scripts
Create a scripts directory in your home folder:
mkdir -p ~/bin
chmod +x ~/bin/*.sh

Add this directory to your PATH in your .bashrc:
export PATH="$HOME/bin:$PATH"

Then run any script from anywhere on your system.

Scheduling Scripts with Cron
Run a health check every day:
0 2 * * * /home/user/bin/health_check.sh

Run backup rotation every 6 hours:
0 */6 * * * /home/user/bin/backup.sh

Run the service checker every 5
*/5 * * * * /home/user/bin/service_check.sh

