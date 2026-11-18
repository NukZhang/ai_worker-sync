# ai_worker-sync

A scheduled trigger for a private Git mirror. This repository contains no application code.

Every five minutes, a GitHub Actions workflow pushes a trigger branch to the private mirror. The private
repository performs the actual merge there, so private commits and logs stay private.
