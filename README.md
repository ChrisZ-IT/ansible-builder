# ansible-builder
A project for building ansible execution environments. Uses ansible-builder and buildx to build the EE and then pushes these images to docker hub.

1. update the requirements.txt/yml with any reqired pip, collection and/or role 
2. Once merged into main, create a new semver release/tag
3. wait for the the github action will run (builds the new image and push it to docker hub)
4. Update your image ref in AAP to the new version.
