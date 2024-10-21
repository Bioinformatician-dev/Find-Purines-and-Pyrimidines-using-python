# Find Purines and Pyrimidines in DNA

Purines and pyrimidines are fundamental components of nucleotides in DNA and RNA and are essential for the storage of information in the cell. They also serve as a basic framework for coenzymes and are involved in numerous enzymatic processes. Alterations in purine or pyrimidine metabolism can have a variety of consequences. For example, disorders of purine metabolism lead to increased amounts of uric acid in blood and can result in gout. Nucleotide synthesis inhibitors are used in tumor therapy; ribonucleotide reductase inhibitor, for instance, inhibits DNA replication in highly proliferative tumor cells by depriving the building blocks of DNA .

## Authors

- [@Salma](https://github.com/Bioinformatician-dev)


## Steps
Step 1: Define the DNA Sequence

DNA = 'AAGATGTGTTAAAGTGTTGTTTAAAAAGGGACCCAAAACAGAGGATATCCATTCCTGAGCTCCTGGCTCATCCATATGTTCAAATTCAAACTCATCAGTTAACAATGGCAGGGAACACTGAGAATGAATTGTTGGCACTGTGTTGATTCTACTCATT'

Step 2: Count Purines (A and G)

a_count = DNA.count('A')
g_count = DNA.count('G')
purine_content = a_count + g_count
print(purine_content)

Counting A and G:
a_count uses the count method to count occurrences of 'A' in the DNA sequence.
g_count counts occurrences of 'G'.

Calculating Purine Content:
purine_content is calculated by adding a_count and g_count.
Output:
The total number of purines is printed.

Step 3: Count Pyrimidines (C and T)

c_count = DNA.count('C')
t_count = DNA.count('T')
pyrimidine_content = c_count + t_count
print(pyrimidine_content)

Counting C and T:
c_count counts occurrences of 'C'.
t_count counts occurrences of 'T'.

Calculating Pyrimidine Content:
pyrimidine_content is the sum of c_count and t_count.
Output:
The total number of pyrimidines is printed.

Step 4: Calculate Percentage of Purines

purine_percent = (purine_content / len(DNA)) * 100
print(purine_percent)

Calculating Purine Percentage:
The length of the DNA sequence is obtained using len(DNA).
The percentage of purines is calculated by dividing purine_content by the total length of the DNA sequence and multiplying by 100.
Output:
The percentage of purines is printed.

Step 5: Calculate Percentage of Pyrimidines

pyrimidine_percent = (pyrimidine_content / len(DNA)) * 100
print(pyrimidine_percent)
Calculating Pyrimidine Percentage:
Similar to purines, the percentage of pyrimidines is calculated and printed.
