#
# Makefile to submit the How_I_Solved_It.txt file 
#
submitdir = bomblab-submit

submit:
	@rm -rf $(submitdir)
	@mkdir -p $(submitdir)
	@cp How_I_Solved_It.txt $(submitdir)
	submit224 $(submitdir) $(submitdir)
	@rm -rf $(submitdir)
