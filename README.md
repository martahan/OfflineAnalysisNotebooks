# OfflineAnalysisNotebooks

This Jupyter Notebook contains the script used to generate plots of observed times taken for a program run which followed a certain subpath.

In order to reproduce these results, clone this repository and clone VyPR, VyPRServer and VyPRAnalysis into this new repository.

git clone git@github.com:martahan/OfflineAnalysisNotebooks.git

cd OfflineAnalysisNotebooks

git clone git@github.com:martahan/VyPRServer.git

git clone git@github.com:martahan/VyPRAnalysis.git

git clone git@github.com:pyvypr/VyPR.git

cd VyPRServer

git clone git@github.com:pyvypr/VyPR.git

cd ..

cp verdicts.db VyPRServer/verdicts.db

rm verdicts.db

Once you run the notebook using 'jupyter notebook' command, follow the steps described in the notebook to obtain the results.
   
