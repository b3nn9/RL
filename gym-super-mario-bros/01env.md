~~~
(base) C:\Windows\system32>conda create -n supermario
Solving environment: done


==> WARNING: A newer version of conda exists. <==
  current version: 4.5.1
  latest version: 4.5.10

Please update conda by running

    $ conda update -n base conda



## Package Plan ##

  environment location: E:\Program\Anaconda3\envs\supermario


Proceed ([y]/n)? y

Preparing transaction: done
Verifying transaction: done
Executing transaction: done
#
# To activate this environment, use
#
#     $ conda activate supermario
#
# To deactivate an active environment, use
#
#     $ conda deactivate


(base) C:\Windows\system32>conda activate supermario

(supermario) C:\Windows\system32>
~~~
~~~
(supermario) C:\Windows\system32>pip install gym-super-mario-bros --user
Collecting gym-super-mario-bros
  Using cached https://files.pythonhosted.org/packages/ce/da/7878c182bb4b2cc0ae0e8a5ffc27a19d95b2b96f7e541cbc96082c64b569/gym_super_mario_bros-3.0.5-py2.py3-none-any.whl
Collecting nes-py>=0.11.0 (from gym-super-mario-bros)
Requirement already satisfied: tqdm>=4.19.5 in e:\program\anaconda3\lib\site-packages (from gym-super-mario-bros) (4.24.0)
Requirement already satisfied: pyglet>=1.3.2 in e:\program\anaconda3\lib\site-packages (from gym-super-mario-bros) (1.3.2)
Collecting numpy>=1.14.2 (from gym-super-mario-bros)
  Using cached https://files.pythonhosted.org/packages/53/d1/2499797c88de95ea3239ad7f6e6a47895fe51aad1aa2a116f50ec9e0ee74/numpy-1.15.0-cp36-none-win_amd64.whl
Requirement already satisfied: matplotlib>=2.0.2 in e:\program\anaconda3\lib\site-packages (from gym-super-mario-bros) (2.1.2)
Requirement already satisfied: pygame>=1.9.3 in e:\program\anaconda3\lib\site-packages (from gym-super-mario-bros) (1.9.4)
Collecting opencv-python>=3.4.0.12 (from gym-super-mario-bros)
  Using cached https://files.pythonhosted.org/packages/f2/f8/42f3ac356fae2500148b7a64b55169212d841987141a3f730708ae128cee/opencv_python-3.4.2.17-cp36-cp36m-win_amd64.whl
Collecting gym>=0.10.5 (from gym-super-mario-bros)
Requirement already satisfied: future in e:\program\anaconda3\lib\site-packages (from pyglet>=1.3.2->gym-super-mario-bros) (0.16.0)
Requirement already satisfied: six>=1.10 in e:\program\anaconda3\lib\site-packages (from matplotlib>=2.0.2->gym-super-mario-bros) (1.11.0)
Requirement already satisfied: python-dateutil>=2.1 in e:\program\anaconda3\lib\site-packages (from matplotlib>=2.0.2->gym-super-mario-bros) (2.6.1)
Requirement already satisfied: pytz in e:\program\anaconda3\lib\site-packages (from matplotlib>=2.0.2->gym-super-mario-bros) (2017.3)
Requirement already satisfied: cycler>=0.10 in e:\program\anaconda3\lib\site-packages (from matplotlib>=2.0.2->gym-super-mario-bros) (0.10.0)
Requirement already satisfied: pyparsing!=2.0.4,!=2.1.2,!=2.1.6,>=2.0.1 in e:\program\anaconda3\lib\site-packages (from matplotlib>=2.0.2->gym-super-mario-bros) (2.2.0)
Requirement already satisfied: requests>=2.0 in e:\program\anaconda3\lib\site-packages (from gym>=0.10.5->gym-super-mario-bros) (2.18.4)
Requirement already satisfied: chardet<3.1.0,>=3.0.2 in e:\program\anaconda3\lib\site-packages (from requests>=2.0->gym>=0.10.5->gym-super-mario-bros) (3.0.4)
Requirement already satisfied: idna<2.7,>=2.5 in e:\program\anaconda3\lib\site-packages (from requests>=2.0->gym>=0.10.5->gym-super-mario-bros) (2.6)
Requirement already satisfied: urllib3<1.23,>=1.21.1 in e:\program\anaconda3\lib\site-packages (from requests>=2.0->gym>=0.10.5->gym-super-mario-bros) (1.22)
Requirement already satisfied: certifi>=2017.4.17 in e:\program\anaconda3\lib\site-packages (from requests>=2.0->gym>=0.10.5->gym-super-mario-bros) (2018.4.16)
Installing collected packages: numpy, opencv-python, gym, nes-py, gym-super-mario-bros
  The scripts conv-template.exe, f2py.exe and from-template.exe are installed in 'C:\Users\b3nn9\AppData\Roaming\Python\
Python36\Scripts' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  The script nes_py.exe is installed in 'C:\Users\b3nn9\AppData\Roaming\Python\Python36\Scripts' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
  The script gym_super_mario_bros.exe is installed in 'C:\Users\b3nn9\AppData\Roaming\Python\Python36\Scripts' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
Successfully installed gym-0.10.5 gym-super-mario-bros-3.0.5 nes-py-0.11.0 numpy-1.15.0 opencv-python-3.4.2.17

(supermario) C:\Windows\system32>
~~~
