# Fiji_COSEM_Predictions_Evaluation

Beanshell script for Fiji to allow a user to evaluate two machine learning predictions for COSEM.

Chooses random subvolumes of the COSEM data to show, displaying the results of the two predictions side by side. Users can select which organelles to display and which one they are scoring.

Evaluation results are saved to a csv file and displayed in a plot.

To use the script, add it to your /Fiji.app/plugins/script directory. When you start Fiji, it should appear under scripts within the Plugins dropdown. If it doesn’t, you may need to go to Help and “Refresh Menus”. If you get any errors with regard to NoClassDefFound, it might be because you need to install n5-imglib2:
