# CRED:Ocular datasets with strong corneal reflections:
## Purpose
  All ocular images included in the CRED database have significant corneal reflection interference. Corneal reflection images can reflect the environmental information around the human eye. However, due to factors such as the shooting method and iris interference, the resolution of corneal reflection images is low, and it is difficult to reconstruct the environmental information in the reflection images clearly and effectively. In addition, due to the corneal reflection interference, the localization of iris and pupil required in the fields of identification, human-computer interaction and attention analysis is often inaccurate or even ineffective. The purpose of collecting the CRED dataset is to help us enhance the quality of corneal reflection images and effectively localize the iris and pupil by annotating the iris, pupil, and eyelid position information and separating the iris interference from the corneal reflection image, so as to help us enhance the quality of corneal reflection images and effectively localize the iris and pupil.
In order to achieve the above goals, we need to specify not only the iris and pupil information of the disturbed eye image, but also the surroundings of the human eye. However, when the human eye is looking at a high-light environment, such as outdoors or on a screen, the position of the pupil is often heavily obscured by reflections, and it is difficult to directly label the iris and pupil positions of images with reflections. Therefore, we need to keep the human eye, the camera position is not moving and the human pupil, iris movement is small (light changes caused by smooth muscle contraction and diastole) under the circumstances of the acquisition of non-reflective or less reflective interference in the eye image to mark the iris, pupil position. In addition, such an eye image with no reflection interference can effectively remove the iris interference to the corneal reflection image.

  However, it is often difficult to acquire such a reflection-free image that kills two birds with one stone. After extensive experiments, we have found that the ambient light reflected by the human eye is replaced by the light from a point source when a strong point source exists at the time of capture. When the location of the point light source is well chosen, the reflection of the point light source in the eye image will be located at the pupil position, and the reflection can be easily removed without affecting the iris texture and structure. In order to control the reflection position, we chose the camera's flash as the point light source, and in addition, we covered the flash with white soft paper, which not only protects the volunteers' eyes, but also ensures that the captured eye images do not have obvious color deviation.
## Structure
The CRED dataset consists of the following:
- Eye images $I_o$(with strong reflections)
- Eye images $I_c$(without strong reflections)
- Regions of Gaze $R_g$
- Corneal Images $I_r$(without iris interference)
- Environment Image $I_s$
## Examples
![ $I_o$ ]("img/du/io.jpg")
![ $I_c$ ]("img/du/ic.jpg")
![ $I_r$ ]("img/du/ir.jpg")
![ $I_s$ ]("img/du/is.jpg")
![ $R_g$ ]("img/du/rg.jpg")
![ $P_o$ ]("img/du/po.jpg")

## Data Acquisition 
Since the dataset contains private and sensitive information such as face, iris, environment, etc., you will need to send a request email to mengqidu@foxmail.com for the download address and unzip password. You are expected to indicate the name of the applicant, his/her workplace and organization, the purpose of data use and the e-mail address of the request.
