clone tensor flow to your desired project folder https://github.com/tensorflow/models.git
download protobuf https://github.com/protocolbuffers/protobuf/releases
add protobuf to path
create environment for anaconda(need to check if it requiered for linux)
conda install protobuf(probably pip in linux need to verify)

go to project folder/models/research

copy use_protobuf and paste it from the repo - https://github.com/BenGreenfield825/Tensorflow-Object-Detection-with-Tensorflow-2.0/blob/master/use_protobuf.py
 run use_protobuf.py 
python use_protobuf.py object_detection/protos protoc

copy setup from \TF2\models\research\object_detection\packages\tf2 and paste it under research

python -m pip install .

conda install numpy 
