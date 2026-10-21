```python
class Casa ():
    def __init__(self):
        self.paredes=None
        self.puerta=None
        self.muebles=None
        
def main():
    casa=Casa()
    casa.paredes=4
    casa.puerta=1
    casa.muebles=20
    
    print(f"mi casa tiene {casa.paredes} paredes y tambien tiene {casa.puerta} puerta y  tambien tiene {casa.muebles}")
    
    
if __name__ == '__main__':
    main()
```