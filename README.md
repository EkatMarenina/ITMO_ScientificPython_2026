# Homework1 (HW1)

### Learn Git Branching Screenshots
Screenshots of my progress through the Learn Git Branching game are saved in the HW1 branch as text files (base64): 1_part_results.txt 2_part_results.txt

### How to convert text files back to images:
```bash
python -c "[open(f'{i}_part_results.png','wb').write(base64.b64decode(open(f'{i}_part_results.txt').read())) for i in ['1','2']]"
