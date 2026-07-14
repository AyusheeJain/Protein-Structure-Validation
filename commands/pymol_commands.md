# PyMOL Commands Used

## Cartoon Representation

```python
hide everything
show cartoon
color marine
```

---

## Hydrogen Bonds

```python
distance hbonds, (donor), (acceptor), 3.5
```

---

## Salt Bridges

```python
select positive, resn ARG+LYS+HIS
select negative, resn ASP+GLU

distance salt_bridges, positive, negative, 4.0

hide labels, salt_bridges
color yellow, salt_bridges
set dash_width,3
```

---

## Hydrophobic Residues

```python
select hydrophobic, resn ALA+VAL+LEU+ILE+MET+PHE+TRP+PRO

show sticks, hydrophobic

color orange, hydrophobic

set stick_radius,0.25
```
