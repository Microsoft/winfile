# ![icon](winfile.png) Windows �t�@�C���}�l�[�W���[

Windows �t�@�C���}�l�[�W���[��32�r�b�g�y��64�r�b�g���̌��݂�Windows(Windows 10���܂�)�ōĂї��p�ł���l�ɂȂ�܂����B

���̃��|�W�g����master�u�����`�ɂ́A�ȉ��̓�̃^�O�����݂��܂��B

1. original_plus: Windows NT4�ŗ��p����Ă��������猻�݂�Windows�ŗ��p�\�ɂ��邽�߂ɍŏ����̕ύX���s��ꂽ�o�[�W�����ł��B
Visual Studio�ŃR���p�C�����Ď��s���鎖���ł��܂��B

2. current master: �V�@�\���ǉ����ꂽ�o�[�W�����ł��B

�s��̕񍐂�@�\�̒�Ă�issues�ɓ��e�܂��̓v�����N�G�X�g�͋C�y�ɍs���Ă��������B

original_plus�u�����`�̃\�[�X�R�[�h�͈�ؕύX���܂���B�܂��A�����R�Ƀ\�[�X�R�[�h�𗘗p���Ă��������B

## �_�E�����[�h
�\�[�X�R�[�h�ł͂Ȃ����s�\�o�C�i���𗘗p�������ꍇ�́A�ȉ��̃����N����_�E�����[�h���Ă��������B

master�u�����`����̍ŐV�ł͌��݂͏������ł��B

[�ŐV����� (v10.0)](https://github.com/Microsoft/winfile/releases/tag/v10.0)

[Original_Plus](https://github.com/Microsoft/winfile/releases/tag/original_plus)

���̑��̃����[�X��[Releases](https://github.com/Microsoft/winfile/releases)�y�[�W���������������B


## ���j

����Windows �t�@�C���}�l�[�W���[��Windows 3.0�Ƌ���1990�N�㏉�߂Ƀ����[�X����܂����B
�ڂ�����[https://en.wikipedia.org/wiki/File_Manager_(Windows)](https://en.wikipedia.org/wiki/File_Manager_(Windows))���������������B

## �X�N���[���V���b�g

![(https://commons.wikimedia.org/wiki/File:Winfile-v10-0-file-manager_%28cropped%29.png)](https://upload.wikimedia.org/wikipedia/commons/6/67/Winfile-v10-0-file-manager_%28cropped%29.png)

[@Speps](https://github.com/speps)���񃊃��N��񋟂��Ē������ɂ��肪�Ƃ��������܂��B
�N�����̉摜��WikiMedia�ɃA�b�v���[�h�����̂��͕�����܂���B

## original_plus �ł̕ύX�_

src�f�B���N�g�����̃\�[�X�R�[�h��2007�N11����Windows NT 4�̃\�[�X�c���[����R�s�[����܂����B
original_plus�^�O�͍ŐV��Windows��WinFile.exe�����s�ł���l�ɕύX�������ł��B����ȊO�̕ύX�͐�������Ă��܂��B

��ȏd�v�ȕύX�͎��̒ʂ�ł��F

1. Visual Studio 2015 �܂��� 2017 �ŗ��p�ł���`�ɕϊ�����܂����B
2. 64�r�b�gWindows�Ŏ��s�\�ɂȂ�܂����B(��: GetWindowLong -> GetWindowLongPtr, LONG -> LPARAM)
3. NT�̃\�[�X�c���[�̕ʂ̏ꏊ�Œ�`����Ă����w�b�_�t�@�C����ǉ����܂����B(��: wfext.h)
4. ���p����Ă��Ȃ��t�@�C�����폜���܂����B(��: winfile.def)
5. 64�r�b�g�̉��Z������������C�u��������C�ɕϊ����܂����B
6. �����V�F��API�����JAPI�ɕϊ����܂����B(�Â��o�[�W�����̕��͓��삵�Ȃ��ׂł��B)

help�f�B���N�g���ɂ�winfile.hlp��winfile.chm�̗����������Ă��܂��B
winfile.hlp��NT4�ɓ����Ă������ł���Windows 10�ł͗��p�ł��܂���B
winfile.chm��Windows 98����R�s�[����܂����B�������Windows 10���痘�p���鎖���ł��܂��B
�������AWinFile.exe��winfile.hlp���N�����悤�Ƃ��Ď��s���܂��B

���[�J���u�����`���쐬����ɂ́A`git checkout -b <your branch> original_plus`�����s���Ă��������B

## original_plus���master v10.0�̕ύX�_

master�u�����`�ɂ�2007�N�ȍ~�̕ύX���܂܂�܂��B����͒P�Ɏ��̌l�I�ȕύX�ł��B
����̕ύX�͎������̃c�[�����g����ŕK�v�ȕ������ɐ�������Ă��܂��B
�Ⴆ�΁A�V����goto�R�}���h���T�|�[�g���܂���C�h���C�u�Ɋւ����񂵂��ێ����Ă��܂���B

����WinFile�͑傫���݌v���ύX����Ă��܂���B

�o�[�W����10.0��2007�N11�����炱��OSS�v���W�F�N�g���쐬�����܂ł̕ύX�S�̂��܂݂܂��B
v10.0�̕ύX�̓R�~�b�g�����ƃ����[�X���������������B

v10.0�ł͈ȉ��̕ύX������܂��F

1. OLE�̃h���b�O���h���b�v���T�|�[�g���܂����B
2. �R���g���[���L�[(��: Ctrl+C)���h���C�u��ύX�������Ɍ��݂̃V���[�g�J�b�g�L�[(��: Ctrl+C -> �R�s�[)�֑Ή����܂����B
3. �؂���(Ctrl+X)�Ɠ\��t��(Ctrl+V)�̓t�@�C���̈ړ���\���܂��B
4. ���E�L�[�𗘗p���ăG�N�X�v���[���̗l�Ƀc���[�r���[�Ńt�H���_��W�J�܂��͐܂肽���ގ����ł���l�ɂȂ�܂����B
5. �R���e�L�X�g���j���[��ǉ����܂����B
6. �t�@�C���A�C�R���̕\�������サ�܂����B
7. F12�L�[�őI�����Ă���t�@�C�����������ŊJ����l�ɂ��܂����B
8. INI�t�@�C���� %AppData%\Roaming\Microsoft\WinFile �Ɉړ����܂����B
9. �t�@�C�������œ��t�𗘗p���ăt�@�C�����i�荞�ގ����ł���l�ɂȂ�܂����B
���̏ꍇ�A�t�@�C���͓��t���ŕ��ёւ����܂��B
10. �t�@�C�������Ŏq�f�B���N�g�����܂ނ��ǂ�����ύX�ł���l�ɂȂ�܂����B
11. Ctrl+K�L�[�����݂̃f�B���N�g���ŃR�}���h�V�F��(ConEmu���C���X�g�[������Ă���ꍇ�A�����炪�N�����܂�)���J�������ł��܂��B
Shift+Ctrl+K�ŊǗ��Ҍ����ŃR�}���h�V�F�����N�����܂��B(�R�}���h�v�����v�g�̂�)
12. �u�ʂ̃f�B���N�g���ֈړ��v(Ctrl+G)�Ő��P�ꂾ�����͂���ƃf�B���N�g���̈ꗗ���\������܂��B
���̒������I�����Ĉړ����鎖���ł��܂��BC�h���C�u�̂݃C���f�b�N�X����Ă��܂��B
13. UI�͉�̓|�C���g(��: �W�����N�V����)�����̂܂ܕ\�����܂��B
14. �ȈՓI�ȗ����̖߂�/�i�ޏ������ǉ�����܂����B(���P���ł��B)
15. ���t���ŕ��ёւ����ł���l�ɂȂ�܂����B

����ȊO�̕ύX�̓\�[�X�R�[�h���Q�Ƃ��Ă��������B

(�������牺�̓��C�Z���X�֘A�̍��ڂł��B�����Ė|�󂹂������̂܂܂ɂ��Ēu���܂����B)

## Contributing

### Contributor License Agreement
As mentioned above, this project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

### What Makes a Good Pull Request for WinFile?
If you are interested in contributing and/or suggesting changes to the actual application, you might find it helpful to [read this post first](https://github.com/Microsoft/winfile/issues/88).

## License

Copyright (c) Microsoft Corporation. All rights reserved.

Licensed under the [MIT](LICENSE) License.

This document is translated by [@Takym](https://github.com/Takym).
