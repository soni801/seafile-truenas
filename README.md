# seafile-truenas

A unified Docker Compose template file for getting a Seafile server up and running in TrueNAS with minimal configuration.

As I was setting up TrueNAS, I realised that Seafile would be the perfect way of serving my files.
However, it turns out that Seafile doesn't have a native TrueNAS application. Even more annoyingly, its setup through
Docker is complicated and time-consuming to replicate in a good way on TrueNAS.

That's why I made this! Originally just to make my own deployment more maintainable, but also as an attempt to help
others in the future. This is a self-contained Docker compose file that you can import into the TrueNAS webinterface,
with only minor configuration options specified at the top of the file.

Please submit a GitHub issue if something doesn't work as expected.

---

I probably don't need this disclaimer, but I'm including it anyway: Please note that this project is not affiliated
in any way with Seafile nor TrueNAS. This is a project entirely maintained by myself, based off Seafile's installation
guide for Docker environments.

