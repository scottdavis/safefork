# SafeFork #

Safe fork allows ActiveRecord models to be ran in child processes safely by wrapping Process.fork

# Usage #
	require 'safefork'
	child = SafeFork.fork do
		Model.some_method
	end