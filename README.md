# Jenkins JNLP Docker Slave

This image is used to run a JNLP slave that can invoke Docker commands on the
host machine. Ensure you mount the Docker socket (e.g. /var/run/docker.sock)
when launching.

*NOTE:* This poses a security risk as the slave is given unrestricted control
over the host Docker service. Be sure to exercise good security by restricting
access to the JNLP slave to trusted actors only.
