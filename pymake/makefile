# makefile created on 2020-08-17 10:43:44.878194
# by pymake (version 1.2.0) for the 'mf6' executable 
# using the 'gfortran' fortran compiler(s).


include ./makedefaults

# Define the source file directories
SOURCEDIR1=../src
SOURCEDIR2=../src/Utilities
SOURCEDIR3=../src/Utilities/OutputControl
SOURCEDIR4=../src/Utilities/TimeSeries
SOURCEDIR5=../src/Utilities/Memory
SOURCEDIR6=../src/Utilities/Observation
SOURCEDIR7=../src/Timing
SOURCEDIR8=../src/Solution
SOURCEDIR9=../src/Solution/SparseMatrixSolver
SOURCEDIR10=../src/Model
SOURCEDIR11=../src/Model/GroundWaterFlow
SOURCEDIR12=../src/Model/Geometry
SOURCEDIR13=../src/Model/ModelUtilities
SOURCEDIR14=../src/Model/GroundWaterTransport
SOURCEDIR15=../src/Exchange

VPATH = \
${SOURCEDIR1} \
${SOURCEDIR2} \
${SOURCEDIR3} \
${SOURCEDIR4} \
${SOURCEDIR5} \
${SOURCEDIR6} \
${SOURCEDIR7} \
${SOURCEDIR8} \
${SOURCEDIR9} \
${SOURCEDIR10} \
${SOURCEDIR11} \
${SOURCEDIR12} \
${SOURCEDIR13} \
${SOURCEDIR14} \
${SOURCEDIR15} 

.SUFFIXES: .f90 .fpp .o

OBJECTS = \
$(OBJDIR)/OpenSpec.o \
$(OBJDIR)/kind.o \
$(OBJDIR)/BaseGeometry.o \
$(OBJDIR)/HashTable.o \
$(OBJDIR)/Constants.o \
$(OBJDIR)/compilerversion.o \
$(OBJDIR)/ims8reordering.o \
$(OBJDIR)/defmacro.o \
$(OBJDIR)/Sparse.o \
$(OBJDIR)/PackageBudget.o \
$(OBJDIR)/Averaging.o \
$(OBJDIR)/Xt3dAlgorithm.o \
$(OBJDIR)/SmoothingFunctions.o \
$(OBJDIR)/SimVariables.o \
$(OBJDIR)/genericutils.o \
$(OBJDIR)/version.o \
$(OBJDIR)/Timer.o \
$(OBJDIR)/List.o \
$(OBJDIR)/ArrayHandlers.o \
$(OBJDIR)/ObsOutput.o \
$(OBJDIR)/mf6lists.o \
$(OBJDIR)/Message.o \
$(OBJDIR)/StringList.o \
$(OBJDIR)/TimeSeriesRecord.o \
$(OBJDIR)/Sim.o \
$(OBJDIR)/Iunit.o \
$(OBJDIR)/InputOutput.o \
$(OBJDIR)/Budget.o \
$(OBJDIR)/MemoryHelper.o \
$(OBJDIR)/sort.o \
$(OBJDIR)/BudgetFileReader.o \
$(OBJDIR)/TableTerm.o \
$(OBJDIR)/PrintSaveManager.o \
$(OBJDIR)/comarg.o \
$(OBJDIR)/CircularGeometry.o \
$(OBJDIR)/RectangularGeometry.o \
$(OBJDIR)/HeadFileReader.o \
$(OBJDIR)/ArrayReaders.o \
$(OBJDIR)/ObsOutputList.o \
$(OBJDIR)/DisvGeom.o \
$(OBJDIR)/BlockParser.o \
$(OBJDIR)/Table.o \
$(OBJDIR)/TimeSeries.o \
$(OBJDIR)/ListReader.o \
$(OBJDIR)/TimeSeriesFileList.o \
$(OBJDIR)/TimeSeriesLink.o \
$(OBJDIR)/NameFile.o \
$(OBJDIR)/Memory.o \
$(OBJDIR)/MemoryList.o \
$(OBJDIR)/MemoryManager.o \
$(OBJDIR)/BaseModel.o \
$(OBJDIR)/PackageMover.o \
$(OBJDIR)/Connections.o \
$(OBJDIR)/ims8linear.o \
$(OBJDIR)/tdis.o \
$(OBJDIR)/Mover.o \
$(OBJDIR)/BaseSolution.o \
$(OBJDIR)/BaseExchange.o \
$(OBJDIR)/SolutionGroup.o \
$(OBJDIR)/UzfCellGroup.o \
$(OBJDIR)/TimeSeriesManager.o \
$(OBJDIR)/DiscretizationBase.o \
$(OBJDIR)/TimeArray.o \
$(OBJDIR)/Observe.o \
$(OBJDIR)/gwf3disu8.o \
$(OBJDIR)/Xt3dInterface.o \
$(OBJDIR)/OutputControlData.o \
$(OBJDIR)/BudgetTerm.o \
$(OBJDIR)/TimeArraySeries.o \
$(OBJDIR)/gwf3dis8.o \
$(OBJDIR)/gwf3disv8.o \
$(OBJDIR)/ObsUtility.o \
$(OBJDIR)/NumericalPackage.o \
$(OBJDIR)/gwf3ic8.o \
$(OBJDIR)/gwf3hfb8.o \
$(OBJDIR)/ObsContainer.o \
$(OBJDIR)/VKDProcess.o \
$(OBJDIR)/BudgetObject.o \
$(OBJDIR)/OutputControl.o \
$(OBJDIR)/TimeArraySeriesLink.o \
$(OBJDIR)/gwt1ic1.o \
$(OBJDIR)/gwf3npf8.o \
$(OBJDIR)/Obs3.o \
$(OBJDIR)/gwt1oc1.o \
$(OBJDIR)/gwf3sto8.o \
$(OBJDIR)/gwf3oc8.o \
$(OBJDIR)/gwf3mvr8.o \
$(OBJDIR)/TimeArraySeriesManager.o \
$(OBJDIR)/BoundaryPackage.o \
$(OBJDIR)/gwf3csub8.o \
$(OBJDIR)/gwt1cnc1.o \
$(OBJDIR)/gwf3chd8.o \
$(OBJDIR)/gwf3wel8.o \
$(OBJDIR)/gwf3obs8.o \
$(OBJDIR)/gwf3rch8.o \
$(OBJDIR)/gwf3sfr8.o \
$(OBJDIR)/gwf3riv8.o \
$(OBJDIR)/gwf3lak8.o \
$(OBJDIR)/gwf3ghb8.o \
$(OBJDIR)/gwt1obs1.o \
$(OBJDIR)/gwt1fmi1.o \
$(OBJDIR)/gwt1mvt1.o \
$(OBJDIR)/gwf3drn8.o \
$(OBJDIR)/gwt1mst1.o \
$(OBJDIR)/NumericalModel.o \
$(OBJDIR)/gwt1adv1.o \
$(OBJDIR)/gwf3maw8.o \
$(OBJDIR)/gwt1ssm1.o \
$(OBJDIR)/gwf3uzf8.o \
$(OBJDIR)/gwt1src1.o \
$(OBJDIR)/gwf3evt8.o \
$(OBJDIR)/GhostNode.o \
$(OBJDIR)/gwf3buy8.o \
$(OBJDIR)/gwt1apt1.o \
$(OBJDIR)/gwt1dsp.o \
$(OBJDIR)/gwt1ist1.o \
$(OBJDIR)/gwt1lkt1.o \
$(OBJDIR)/NumericalExchange.o \
$(OBJDIR)/gwt1uzt1.o \
$(OBJDIR)/gwf3.o \
$(OBJDIR)/gwt1mwt1.o \
$(OBJDIR)/GwfGwfExchange.o \
$(OBJDIR)/gwt1sft1.o \
$(OBJDIR)/gwt1.o \
$(OBJDIR)/NumericalSolution.o \
$(OBJDIR)/GwfGwtExchange.o \
$(OBJDIR)/SimulationCreate.o \
$(OBJDIR)/mf6core.o \
$(OBJDIR)/mf6.o

# Define the objects that make up the program
$(PROGRAM) : $(OBJECTS)
	-$(FC) $(OPTLEVEL) -o $@ $(OBJECTS) $(LDFLAGS)

$(OBJDIR)/%.o : %.f90
	@mkdir -p $(@D)
	$(FC) $(OPTLEVEL) $(FFLAGS) -c $< -o $@ $(INCSWITCH) $(MODSWITCH)

$(OBJDIR)/%.o : %.fpp
	@mkdir -p $(@D)
	$(FC) $(OPTLEVEL) $(FFLAGS) -c $< -o $@ $(INCSWITCH) $(MODSWITCH)

