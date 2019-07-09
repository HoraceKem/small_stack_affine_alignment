# small_stack_affine_alignment
This is a repo forked from [Rhoana](http://github.com/Rhoana/small_stack_affine_alignment)

## Description
A fast affine only registration for a small stack

##Installation
1. Create a new environment
```
conda create -n ENV_NAME python=3.7
conda activate ENV_NAME
```

2. Install rh_config
```
$ git clone git@github.com:HoraceKem/rh_config.git
$ cd rh_config/
$ pip install -r requirements.txt
$ pip install --editable .
```

3. Install rh_logger
```
$ git clone git@github.com:HoraceKem/rh_logger.git
$ cd rh_logger/
$ pip install -r requirements.txt
$ pip install --editable .
```

4. Install this repo
```
$ git clone git@github.com:HoraceKem/small_stack_affine_alignment.git
$ cd small_stack_affine_alignment/
$ pip install -r requirements.txt
$ pip install --editable .
```

## Usage
+For IDE users:
   +Choose the former conda environment as the interpreter.
   +Open *aligner.py*
   +Change the input directory to your local path
+For terminal user:
```
conda activate ENV_NAME
cd path/to/small_stack_affine_alignment
python aligner.py
```
