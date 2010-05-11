# SafeFork #

Safe fork allows active record models to be ran in child processes safely by wrapping Process.fork

# Usage #
	require 'safefork'
	child = SafeFork.fork do
		Model.some_method
	end