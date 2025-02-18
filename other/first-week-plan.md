# Rencana Pembelajaran Minggu Pertama

## Overview

Dokumen ini berisi rencana detail pembelajaran untuk minggu pertama, fokus pada pembangunan fondasi dasar astronomi dan setup lingkungan belajar.

## Persiapan Awal

### Setup Lingkungan Belajar

- [X] Siapkan area belajar yang nyaman
- [X] Install software dasar:
  - Python 3.x
  - Visual Studio Code
  - Anaconda Distribution
  - Git
- [X] Setup GitHub account
- [X] Create learning repository
- [X] Download Stellarium (free planetarium software)

### Resources yang Dibutuhkan

- [X] Download materi pembelajaran:
  - Basic Python tutorials
  - Astronomy fundamentals PDFs
  - Math review materials
- [X] Bookmark website penting:
  - astronomy.com
  - space.com
  - arxiv.org/archive/astro-ph

## Jadwal Harian

### Senin: Fondasi Python & Astronomi

#### Deep Learning (01:00-04:30)

- [X] Python Basics:
  - Variables & data types
  - Basic operations
  - Control structures
- [ ] Astronomy Introduction:
  - Basic terminology
  - Celestial coordinates
  - Star magnitudes

#### Review Malam (19:30-20:30)

- [ ] Practice Python exercises
- [ ] Create simple star magnitude calculator
- [ ] Review terminology learned

### Selasa: Matematika & Observasi

#### Deep Learning (01:00-04:30)

- [ ] Math Review:
  - Basic algebra
  - Trigonometry fundamentals
  - Angular measurements
- [ ] Stellarium Tutorial:
  - Interface familiarization
  - Basic navigation
  - Finding objects

#### Review Malam (19:30-20:30)

- [ ] Practice trigonometry problems
- [ ] Virtual sky observation using Stellarium
- [ ] Document learned concepts

### Rabu: Programming Tools

#### Deep Learning (01:00-04:30)

- [ ] Git Basics:
  - Repository setup
  - Basic commands
  - Commit practice
- [ ] IDE Familiarization:
  - VS Code setup
  - Extensions installation
  - Workspace organization

#### Review Malam (19:30-20:30)

- [ ] Practice Git commands
- [ ] Create first project repository
- [ ] Document setup process

### Kamis: Scientific Python

#### Deep Learning (01:00-04:30)

- [ ] NumPy Introduction:
  - Arrays
  - Basic operations
  - Math functions
- [ ] Matplotlib Basics:
  - Simple plotting
  - Graph customization
  - Saving figures

#### Review Malam (19:30-20:30)

- [ ] Create simple data plots
- [ ] Practice array operations
- [ ] Document new functions learned

### Jumat: Astronomi Praktis

#### Deep Learning (01:00-04:30)

- [ ] Star Charts:
  - Reading basics
  - Constellation patterns
  - Coordinate systems
- [ ] First Mini Project:
  - Plot star positions
  - Basic constellation drawer
  - Simple magnitude calculator

#### Review Malam (19:30-20:30)

- [ ] Project implementation
- [ ] Debug and improve code
- [ ] Document progress

### Sabtu: Integration & Practice

#### Deep Learning (01:00-04:30)

- [ ] Combine Learning:
  - Python + Astronomy calculations
  - Plotting celestial objects
  - Basic data analysis
- [ ] Project Work:
  - Continue mini project
  - Add new features
  - Improve code structure

#### Evening Session (19:30-22:30)

- [ ] Practical observation (if weather permits)
- [ ] Virtual observation (if cloudy)
- [ ] Document observations

### Minggu: Review & Planning

#### Morning Session (08:00-10:00)

- [ ] Weekly Review:
  - Consolidate notes
  - Review code written
  - Organize GitHub repository
- [ ] Progress Assessment:
  - What worked well
  - What needs improvement
  - Adjust next week's plan

#### Evening Session (19:30-20:30)

- [ ] Prepare for next week:
  - Review learning materials
  - Setup next projects
  - Update learning repository

## Project Minggu Pertama

### Simple Star Catalog

Membuat program sederhana yang dapat:

- [ ] Menyimpan data bintang:
  - Nama
  - Magnitude
  - Koordinat
- [ ] Menampilkan data dalam plot
- [ ] Melakukan pencarian sederhana
- [ ] Menyimpan data ke file

```python
# Example code structure
class Star:
    def __init__(self, name, magnitude, ra, dec):
        self.name = name
        self.magnitude = magnitude
        self.ra = ra
        self.dec = dec

class StarCatalog:
    def __init__(self):
        self.stars = []

    def add_star(self, star):
        self.stars.append(star)

    def plot_stars(self):
        # Add plotting code here
        pass
```

## Tracking Progress

### Daily Log Template

```markdown
# Daily Learning Log
Date: [Date]
Topics Covered:
- Topic 1
- Topic 2

Code Written:
- Description of code
- Link to repository

Challenges:
- Challenge 1
- Challenge 2

Tomorrow's Goals:
- Goal 1
- Goal 2
```

### Weekly Assessment

- [ ] Python concepts learned
- [ ] Astronomy concepts understood
- [ ] Code written and committed
- [ ] Projects completed
- [ ] Challenges faced
- [ ] Solutions found

## Resources & References

### Python Learning

- Python.org tutorial
- Real Python website
- Automate the Boring Stuff

### Astronomy Basics

- Stellarium User Guide
- Sky & Telescope website
- NASA astronomy picture of the day

### Mathematics

- Khan Academy
- Paul's Online Math Notes
- 3Blue1Brown videos

## Notes

- Focus on understanding basics
- Practice code regularly
- Document everything
- Don't rush concepts
- Ask questions in forums
- Keep backup of all code
- Regular commits to GitHub
