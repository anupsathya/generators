# Art Caption Generator

This workflow helps you generate consistent and beautifully formatted captions for art projects using Affinity Publisher's Data Merge feature.

## Prerequisites

- [Affinity Publisher 2](https://affinity.serif.com/en-us/publisher/)
- A CSV file containing your caption data

## Steps

1. **Open the Template**
   - Open the file `at-caption.afpub` in Affinity Publisher.

2. **Prepare Your Data**
   - Create a CSV file with the following **column headers**:
     - `Title`: The title of the artwork
     - `Name`: The artist's name
     - `Description`: A short description or context for the piece
   - Example:
     ```csv
     Title,Name,Description
     Mirror Fragment,Anup S.,A piece exploring broken perception through reflective surfaces.
     ```

3. **Load the Data in Affinity Publisher**
   - Go to `Window` > `Data Merge Manager...`
   - Click the folder icon to load your CSV file
   - Ensure the column names match exactly: `Title`, `Name`, `Description`
   - Use the preview option to check that your data is mapping correctly

4. **Generate Captions**
   - Insert merge fields in your layout as needed using the Data Merge Manager
   - Once ready, click `Generate` to produce captioned versions

## Resources

- Official Affinity Publisher Data Merge Guide:  
  [https://affinity.help/publisher2/en-US.lproj/index.html?page=pages/Advanced/dataMerge.html&title=Data%20merge](https://affinity.help/publisher2/en-US.lproj/index.html?page=pages/Advanced/dataMerge.html&title=Data%20merge)

---

