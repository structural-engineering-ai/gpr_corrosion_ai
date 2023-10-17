# gpr_corrosion_ai  <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAFAAAABQCAYAAACOEfKtAAAACXBIWXMAAAsTAAALEwEAmpwYAAABs0lEQVR4nO3ZTytEURjH8Z+/kUnydixsWLFiNztWrNixYsWbsZySWVlYqCkLpZRSSkqSlBfw6NYzZcfMc+8915nvp86C3Oc4X2cyNRIAAABQD/NVxc8POvtfMgISMCnjBhIwKeMGEjAp4wYSMCnjBhIwKeMGDh7LGrD+JWvQyobxEiZgUsYNJGBSxg2UJiTdD/nfL0XA337HB0mTqtF24O2DNTBgsbZUkylJj75pO4OXcNufeZI0rRrs+oZ3ksYzCFic4daf21HFZiQ9+2YbQ85oWsDCpj/3ImlWFdr3jW4kjWUUsDhLz5/dU0XmJL36JmuBOdbAgIV1f/ZNUksVOPQNeoHb13TXfsaDsge3/C9TDF9Rvlb9jO+S5sscfOyDr5S/Sz/rUVkDFyR9+NBl5W/Jz/opabGMgac+sKvR0fUzn5Qx7MuHXfz43pmkTsZfn/uZi7OH9d8aFJv0dUbgayvro4DsPlP4IwIGETCIgEEEDCJgEAGDCBhEwCACBhEwiIBBBAwiYBABgwgYRMAgAgYRMIiAQQQMImAQAYMIGETAIAI2LeCorjAb8QUAAAAAUFa+ATv+QHRuzXMUAAAAAElFTkSuQmCC">
Experimenting with deep learning models to see the viability of detecting corrosion of rebar in reinforced concrete structures.
The model was made using pytorch <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" width="15" height="15">.  This was a proof of concept done on small data - it will be able to infer on data from outside the original data files <not included> or training data provided.

#### Notes:
1. Paths in the model to the data will need to be manually updated prior to running.
2. Models generally test around 60 - 85% with 1000 epochs.

#### License:
MIT License
