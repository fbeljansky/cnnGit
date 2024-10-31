primero activar el entorno virtual 
OJO ver que estes trabajando con el entorno del .env

.\env\Scripts\activate en windows
despues instale 
pip install tensorflow pandas
pip install tensorflow numpy scikit-learn
pip install keras-preprocessing
 python3 -m pip install tensorflow[and-cuda]
  pip install keras==2.12
pip install --upgrade numpy h5py


Recomendaciones:

    Revertir a la Versión Compatible de numpy:
    Dado que tensorflow-intel requiere una versión específica de numpy, puedes intentar revertir a esa versión compatible:

    bash

pip install numpy==1.26.4

Esto instalará la versión específica de numpy que es compatible con tensorflow-intel.

Desinstalar tensorflow-intel y Cambiar a la Versión Estándar de TensorFlow:
Si el problema persiste, considera desinstalar tensorflow-intel y cambiar a la versión estándar de TensorFlow. Esto puede resolver problemas de compatibilidad y asegurar que todas las dependencias funcionen correctamente juntas:

bash

pip uninstall tensorflow-intel
pip install tensorflow

decidi usar pytorch ya que tensorflow no me funcionaba
PARA NUEVO ENFOQUE pytorch
pip install torch torchvision pandas opencv-python matplotlib
