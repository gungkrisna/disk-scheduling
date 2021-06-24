# disk-scheduling
<img width="1137" alt="Screen Shot 2021-06-25 at 00 25 18" src="https://user-images.githubusercontent.com/35645656/123299189-d6ec3580-d54b-11eb-8e9a-e7dce4848509.png">
A Jupyter notebook that implemented using Python which computes also visualizes LOOK, SCAN, and SSTF disk-scheduling algorithms.

## Installation
If you are familiar with Jupyter, click below to launch the program notebooks in Jupyter powered by Google Colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Xutn224R8PPU3l0GyJuPqjHStwCnqfSk?usp=sharing)

## Usage
### SCAN & LOOK
Direction argument can be stated depends on the user with two default values; left and right. Direction argument is optional so user can leave it blank.

Create new cell on Jupyter Notebook and run this code below.

```python
queue=[83, 35, 10, 90, 45, 80, 20, 50, 65]
head=25

LOOK(head, queue, direction="right")
```

### SSTF
Shortest Seek Time First (SSTF) algorithm will decide the direction itself depends on shortest seek time. It means direction argument does not needed while calling the function.

Create new cell on Jupyter and run this code below.
```python
queue=[83, 35, 10, 90, 45, 80, 20, 50, 65]
head=25

SSTF(head, queue, direction="right")
```

## Variable definition
<b>h</b> = current head position </br>
<b>m</b> = current seek time </br>
<b>q</b> = current queue element </br>
<b>c</b> = counter </br>

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.


## License
[MIT](https://github.com/gungkrisna/disk-scheduling/blob/main/LICENSE)
