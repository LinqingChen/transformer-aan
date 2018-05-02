# transformer-aan
source code for "Accelerating Neural Transformer via an Average Attention Network"

Notice: the source code is developed upon <a href="https://github.com/thumt/THUMT">THUMT</a>
<<<<<<< HEAD

# file structure:
`train.sh`: provides the training script with our used configuration.
`test.sh`: provides the testing script.

`learning.lg`, `inference.lg` and directory `train` and `test` are generated on WMT14 en-de translation task.
`learning.lg` contains the log of training procedure.
`inference.lg` contains the log of testing procedure.
`train/eval/log` records the approximate BLEU score on development set during training.
`test/` contains the decoded development and test dataset, for researchers who are interested in the translations generated by our model.

The processed WMT14 en-de dataset can be found at <a href="https://drive.google.com/open?id=15WRLfle66CO1zIGKbyz0FsFmUcINyb4X">Transformer-AAN-Data</a>. (Original files are downloaded from Stanford NMT website.)


For any further comments or questions, please email <a href="mailto:zb@stu.xmu.edu.cn">Biao Zhang</a>.
=======
>>>>>>> 9ac260ad3aac118d711fb00fec9beed007d8152a
