0.2 (unreleased)
----------------

- Added velocity_marked_npairs_3d and velocity_marked_npairs_xy_z to pair_counters

- Deleted mock_observables.nearest_neighbor function

- Added new npairs_per_object_3d. 

- Added new marked pair counters marked_npairs_3d and marked_npairs_xy_z

- Added new pair counters npairs_s_mu, npairs_jackknife_3d, npairs_projected, npairs_xy_z

- Replaced npairs function with npairs_3d, which has the exact same API but is 30%-50x faster. 

- Halotools is now Python 3.x compatible

0.1 (2016-03-13)
----------------

- Initial release
