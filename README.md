# SBI_electroral_bond_compare


Python library
Basic example

bash
"""
import pdfplumber

with pdfplumber.open("path/to/file.pdf") as pdf:
    first_page = pdf.pages[0]
    print(first_page.chars[0])
"""
