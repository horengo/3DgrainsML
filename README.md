Jupyter notebook with the code executing the algorithm for the extraction of traditional measures from 3D models and their classification using conventional ML techniques discussed in the paper: <br>
Orengo, H.A.; Esmoris, J.; Berganzo-Besga, I.; Lumbreras, F.; Aliende, P.; Wallace, M.; Livarda, A. <br> New computational approaches to morphometrics: combining 3D complex shape representation and machine learning for shape analysis. <br>
Submitted to the Journal of Archaeological Science

## Running in Google Colab

The notebook can be executed on Google Colab. Open
`3DgrainsML.ipynb` in Colab and run the **Setup paths** code cell
near the top of the notebook. This cell mounts Google Drive and
defines the variables `BASE_FOLDER` and `MAPPING_ROOT` used
throughout the rest of the code.

Update these variables if your 3D models or CSV files are stored in a
different location. By default they point to directories inside your
Google Drive:

```
BASE_FOLDER = '/content/drive/MyDrive/3D_models/oriented_SH'
MAPPING_ROOT = '/content/drive/MyDrive/ProofsML/OrientedMatched_40K_L50'
```

Make sure the required STL models and any existing CSV files are
available in these directories before running the subsequent cells.
