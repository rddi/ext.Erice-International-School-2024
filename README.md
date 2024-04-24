```                       
                       ((.                                                      
                 ((((((.                                                        
                ((((((((                                                        
                 ((((((,                                                        
        ((         (((.      .((((,           //                                
     *(((((((  */        (((((((((((((    &&&&&&&&&&  ,&&&%&&&&&&   &&&&&&&&    
      ((((((((((((              /(((((   &&&&    &&&% ,&&&    %&&&  &&&         
           ((*                           &&&&/*,,,..  ,&&&    (&&&  &&&%%%&     
                  */    (((((.            &&&&    &&  ,&&&   &&&&   &&&         
                ((((,      ((((((           &&&&&&&   ,&&&&&&&,     &&&         
         .((((((((((        (((((((                                             
          (((((((((          ((((((                                             
                                                                                


8888888b.   .d8888b.     8888888b.  8888888b. 8888888          888     888 888    d8P  
888   Y88b d88P  "88b    888  "Y88b 888  "Y88b  888            888     888 888   d8P   
888    888 Y88b. d88P    888    888 888    888  888            888     888 888  d8P    
888   d88P  "Y8888P"     888    888 888    888  888   d8b      888     888 888d88K     
8888888P"  .d88P88K.d88P 888    888 888    888  888   Y8P      888     888 8888888b    
888 T88b   888"  Y888P"  888    888 888    888  888            888     888 888  Y88b   
888  T88b  Y88b .d8888b  888  .d88P 888  .d88P  888   d8b      Y88b. .d88P 888   Y88b  
888   T88b  "Y8888P" Y88b8888888P"  8888888P" 8888888 Y8P       "Y88888P"  888    Y88b
```

# ext.Erice-International-School-2024

## Installing ultralytics, pycocotools and opencv

1) Create a python virtual enviroment using pyenv module

```
$ mkdir my_env_name
$ python3 -m venv my_env_name
```

2) activating your enviroment
```
$ source my_env_name/bin/activating
(my_env_name)$
```

3) install packages
```
(my_env_name)$ pip install --upgrade pip 
(my_env_name)$ pip install ultralytics
```

4*) fixing headless opencv error

```
(my_env_name)$ pip install opencv-python-headless
```

5) installing pycocotools (needed for convert json labels to coco)

```
(my_env_name)$ pip install pycocotools
```

6) installing jupyter and ipykernel

```
(my_env_name)$ pip install jupyter ipykernel
```

7) linking the enviroment to my jupyter kernel 

```
(my_env_name)$python -m ipykernel install --user --name my_env_name --display-name "my_env_name"
```

## Installing langchain and gpt
```
$ mkdir csv_env_name
$ python3 -m venv csv_env_name
```

2) activating your enviroment
```
$ source my_env_name/bin/activating
(csv_env_name)$
```

3) install packages
```
(csv_env_name)$ pip install --upgrade pip
(csv_env_name)$ pip install -r csv_agents_req.txt
```

4) installing jupyter and ipykernel

```
(csv_env_name)$ pip install jupyter ipykernel
```

5) linking the enviroment to my jupyter kernel 

```
(csv_env_name)$python -m ipykernel install --user --name csv_env_name --display-name "csv_env_name"
```


