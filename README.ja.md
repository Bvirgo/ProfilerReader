# ProfilerReader
�v���t�@�C���[�̃��O�t�@�C������͂���c�[���ł�<br />
Read this in other languages: [English](README.md), ���{��<br />

## �T�v
���̃c�[���� "Unity Profiler".
For example, generate csv files that shows Samples allocating many Managed Heap from "Unity Profiler" binary log.

## �Ή��o�[�W����
5.6 / 2017.1 / 2017.2 / 2017.3 / 2017.4 / 2018.1 / 2018.2 / 2018.3 / 2018.4 /2019.1/2019.2/2019.3

## GUI����ɂ���

## CUI����ɂ���
### �T���v���R�}���h
Unity.exe -batchMode -projectPath "ProjectPath" -logFile .\Editor.log -executeMethod UTJ.ProfilerReader.CUIInterface.ProfilerToCsv -PH.inputFile "Binary logFile(.data/.raw)" -PH.timeout 2400 -PH.log

�o�C�i�����O�t�@�C���Ɠ����ꏊ�ɃT�u�t�H���_���쐬���A�������CSV�t�@�C������������܂��B

## CSV Files:


