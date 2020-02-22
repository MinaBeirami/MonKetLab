MonKetLab
==========
predicting marker share of series for  Montreal's TV channel

### Setup Python environment                                                                                                                                                              
                                                                               
```bash                                                                        
sudo apt-get install python3-pip python3-dev                                   
sudo pip3 install virtualenvwrapper                                            
echo "export VIRTUALENVWRAPPER_PYTHON=`which python3.6`" >> ~/.bashrc          
echo "alias v.activate=\"source $(which virtualenvwrapper.sh)\"" >> ~/.bashrc  
source ~/.bashrc                                                               
v.activate                                                                     
mkvirtualenv --python=$(which python3.6) --no-site-packages monketlab            
```                                                                            
                                                                               
#### Activating virtual environment                                            
                                                                               
```bash                                                                        
workon monketlab                                                                 
```                                                
