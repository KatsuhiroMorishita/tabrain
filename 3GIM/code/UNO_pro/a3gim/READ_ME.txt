a3gim R3.0 �����[�X�m�[�g
                                                            2014.12.10

3GIM�p��Arduino���C�u����a3gim R3.0�ł��B
�@�\�I�ɂ́Aa3gs R3.0�Ɠ����ł��B


�ya3gs�Ƃ̍��قɂ��āz

a3gim�ł́A�d�������SMS��M���̊��������݂̂��ύX�ƂȂ��Ă��܂��B
�ȉ��A�ύX�_��������܂��F

- int start(int pin)
�@�@�w�肵��pin��d������Ɏg�p���܂��B
�@�@�f�t�H���g(pin�w��Ȃ�)�ł́A�d������͍s���܂���̂�
�@�@���ON�ƂȂ�܂��B
�@�@����pin��1�ȏ�̔ԍ����w�肵�Ă��������B
�@�@���Ƃ��΁AArduino��D6��3GIM��1�ԃs���ɐڑ������ꍇ�́A
�@�@�@�@a3gs.start(6)
�@�@�̂悤�ɌĂяo���Ă��������B

- void shutdown()
�@�@�d��������s���Ă���ꍇ�A3GIM�̓d����OFF�ɂ��܂��B

- onSMS()
�@�@3GIM�ł�SMS����M���Ă��������܂���B

�ya3gim���C�u�����̎g�����z

a3gim���C�u�����́AArduino UNO/Pro����3GIM�𗘗p���邽�߂̃��C�u�����ł��B
���L�̌������s���Ă��炲�g�p���������B

- Arduino D2-3,D6-13,A0-5�̂����ꂩ���͐ڑ��Ȃ�  -->  3GIM #1(PWR_SW)
- Arduino D4  -->  3GIM #3(TX)
- Arduino D5  -->  3GIM #2(RX)
- Arduino 5V  -->  3GIM #4(IOREF)
- Arduino GND -->  3GIM #6(GND)
- 3.7V�d���܂��̓��`�E���d�r�Ȃ�  --> 3GIM #5(VCC)

--
