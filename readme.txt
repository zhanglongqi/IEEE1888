---------------------------------------------------------
�@IEEE1888 C����� �v���g�R���X�^�b�N�E�\�t�g�E�F�A
  �@�@�@�@                                 ���: �����G��
          �@�@�@�@                    �o�[�W����: v201310
---------------------------------------------------------

�P�D�͂��߂�
�@���̃p�b�P�[�W�ɂ́AC�����IEEE1888�v���g�R���X�^�b�N��
�@�\�[�X�R�[�h�Ŋ܂܂�Ă��܂��B

�@�t�@�C���\���͈ȉ��̒ʂ�ł��B
�@- ieee1888.h �@�@�@�@�@�@�@�@���C���̃w�b�_�E�t�@�C��
�@- ieee1888_client.c�@�@�@�@�@IEEE1888��query/data���\�b�h�̃N���C�A���g�ʐM�X�^�u
�@- ieee1888_object_factory.c�@IEEE1888�I�u�W�F�N�g(transport��body��)�̐����H��
�@- ieee1888_sample_gw.c �@�@�@GW�̃T���v������
�@- ieee1888_sample_app.c�@�@�@APP�̃T���v������
�@- ieee1888_server.c�@�@�@�@�@IEEE1888��query/data���\�b�h�̃T�[�o�ʐM�X�^�u
�@- ieee1888_util.c�@�@�@�@�@�@�֗��ȋ@�\(�I�u�W�F�N�g�̃_���v�\����)�̏W��
�@- ieee1888_XMLgenerator.h�@�@XML�V���A�����̂��߂̃w�b�_�E�t�@�C��
�@- ieee1888_XMLgenerator.c�@�@IEEE1888�I�u�W�F�N�g��XML�V���A�����@�\(������)����
�@- ieee1888_XMLparser.h �@�@�@XML�f�V���A�����̂��߂̃w�b�_�E�t�@�C��
�@- ieee1888_XMLparser.c �@�@�@IEEE1888�I�u�W�F�N�g��XML�f�V���A�����@�\(��͋@)����
�@- ieee1888_datapool.h �@�@�@ �đ��M�҂��f�[�^�̕ۊǋ@�\�����̃w�b�_�E�t�@�C��
�@- ieee1888_datapool.c �@�@�@ �đ��M�҂��f�[�^�̕ۊǋ@�\����
�@- Makefile �@�@�@�@�@�@�@�@�@make�r���h���s�ݒ�t�@�C��
�@- readme.txt �@�@�@�@�@�@�@�@���̃t�@�C��

�Q�D�r���h���@
�@Linux���ɂāA
�@$ make
�@�����s���܂��B

�@�ȏ�ŁA
�@�@ieee1888_sample_app ����� ieee1888_sample_gw 
�@�̎��s�t�@�C������������܂��B
�@����Ńr���h�͊����ł��B

�R�D���ǂ̕��@
�@ieee1888_sample_gw.c �́AFETCH, WRITE�T�[�o�̃T���v���ƂȂ��Ă��܂��B
�@ieee1888_sample_app.c �́AFETCH, WRITE�N���C�A���g�̃T���v���ƂȂ��Ă��܂��B
�@�������ЂȌ^�ɂ��A�V���ȃA�v���P�[�V����(GW, APP��)���������邱�Ƃ��ł��܂��B

�@����ȊO�̃t�@�C���́A���C�u�����Ƃ��Ďg�p����̂ŁA�ҏW����K�v�͂���܂���B
�@�ڍׂ́A�uIEEE1888�v���g�R�����ȏ� (�C���v���X�W���p����)�v���Q�Ƃ��Ă��������B


�S�D�Ɛӎ���
�@�{�\�t�g�E�F�A���g�p���Đ��������ۂɂ��ẮA
�@��҂���т��̊֘A�g�D�͐ӔC�𕉂����˂܂��̂ŁA
�@�\�߂��������������B

�T�D���C�Z���X
�@BSD���C�Z���X�ł��B
�@�l�E���p���킸�A�����p���������܂��B

�U�D�X�V���e
�@�E v201310�� <- v201212�ł̍X�V
�@�@- IPv6 only���ł����삷��悤�ɉ��� (special thanks to Hiroyuki Ikegami)
�@�@- ieee1888_client �� ieee1888_server�ł̐ڑ����s�������� (special thanks to Motomasa Tanaka (motomasa-tanaka@mayekawa.co.jp))
�@�@- �\�[�X�R�[�h�Ƀ��C�Z���X����ǉ�
�@�@- ieee1888_server gcc�r���h���ɏo�� warning: format not a literal ... ������

�V�D�o�O�̕�
�@�����G�� ochiai@vdec.u-tokyo.ac.jp �ւ��A�����������B