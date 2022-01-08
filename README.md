# Improper orders
Which atom is central in your improper torsion?

| Package    | Improper type       | Central atom | Links and notes                                                                                                                                            |
|------------|---------------------|--------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| AMBER      | Periodic            | 3 (or 2)     | Torsions can be reversed for 1-4 torsions. https://github.com/MDAnalysis/mdanalysis/issues/2386 https://github.com/openmm/openmm/issues/220#issue-22877306 |
| ParmEd     | Periodic            | 3            | https://github.com/MDAnalysis/mdanalysis/issues/2386                                                                                                       |
| ParmEd     | Harmonic            | 1            | https://github.com/MDAnalysis/mdanalysis/issues/2386                                                                                                       |
| Gromacs    | Periodic            | 3            | https://github.com/MDAnalysis/mdanalysis/issues/2386                                                                                                       |
| Gromacs    | Harmonic            | 1            | https://github.com/MDAnalysis/mdanalysis/issues/2386                                                                                                       |
| OpenFF     | Smirnoff (periodic) | 2            | https://github.com/openforcefield/openff-toolkit/issues/746#issuecomment-710574144                                                                         |
| OpenFF     | Amber               | 3            | https://github.com/openforcefield/openff-toolkit/issues/746#issuecomment-710574144                                                                         |
| CHARMM     | all?                | 1            | https://github.com/michellab/Sire/issues/193#issue-303038454                                                                                               |
| MDAnalysis | all                 | any          | MDAnalysis does not check connectivity.                                                                                                                    |
| NAMD       | all?                | 1            | Follows CHARMM                                                                                               
