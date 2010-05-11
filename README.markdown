# SafeFork #

Safe fork allows ActiveRecord models to be ran in child processes safely by wrapping Process.fork

# Usage #
	require 'safe_fork'
	child = SafeFork.fork do
		Model.some_method
	end