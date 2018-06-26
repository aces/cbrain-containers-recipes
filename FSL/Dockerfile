FROM neurodebian:artful-non-free

#####################################################
#                                                   #
# MCIN (McGill Centre for Integrative Neuroscience) #
#                                                   #
# Singularity recipe for FSL to build a container   #
# used in CBRAIN (https://github.com/aces/cbrain)   #
#                                                   #
#####################################################

RUN apt-get update
RUN apt-get install -y fsl-complete

ENV FSLDIR=/usr/share/fsl/5.0 
ENV FSLOUTPUTTYPE=NIFTI_GZ 
ENV PATH=/usr/lib/fsl/5.0:$PATH 
ENV FSLMULTIFILEQUIT=TRUE 
ENV POSSUMDIR=/usr/share/fsl/5.0 
ENV LD_LIBRARY_PATH=/usr/lib/fsl/5.0:$LD_LIBRARY_PATH 
ENV FSLTCLSH=/usr/bin/tclsh 
ENV FSLWISH=/usr/bin/wish 
ENV FSLOUTPUTTYPE=NIFTI_GZ
