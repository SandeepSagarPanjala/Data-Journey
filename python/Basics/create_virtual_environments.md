conda create --name myenv python=3.10
conda activate myenv
conda install pandas numpy matplotlib scikit-learn
conda deactivate

conda activate <your_environment_name>
if not given base environment will be taken by default

conda list -n <your_environment_name>
shows the list of packages in your environments

conda remove --name <your_environment_name> --all
deleted the mentioned environment
