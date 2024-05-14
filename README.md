To run this code 1st create a new conda environment then install these following libraries
pip install gym
pip install gym[atari]
pip install gym[accept-rom-license]
pip install tesnsorflow
But if u want to run on GPU then
then mention python==3.10 when creating a new environment for this
Then install below packages 
conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0]
python -m pip install "tensorflow<2.11"
