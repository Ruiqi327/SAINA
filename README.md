2024.7.27 Statement of Originality

All codes are edited by Ruiqi Zhou, which are completely open sourced and can be read, copied and used by anyone.  However, we'd love to kindly suggest you to acknowledge the source when using this code, which will greatly encourage us to continue our open source work. If you have any problem reading this code, feel free to e-mail me at zhouruiqi@stu.scu.edu.cn.

Current version of this code aims to make it easier for reviewers to evaluate our paper submitted to IEEE CONTROL SYSTEMS LETTERS. When the paper is officially accepted, we shall update a new version with more detailed explanations. The following are some cases and explanations that we have not included in our manuscript due to limitted space:

## What happens if a link of the manipulator changes its length during the tracking of the Lisaru-III graphic?
The proposed SAINA still performs well if the link changes its length during the tracking of the Lisaru-III graphic!

![image](https://github.com/user-attachments/assets/ba9bd96e-47a0-4dce-8287-3e646bfefc41)
Convergence validation with link length: Link1=1.2m, Link2=1m, Link3=0.8m in t ≤ 7.5s and Link1=0.8m, Link2=1.2m, Link3=1m in t > 7.5s. (a) Trajectory of f(t) during 15-20s. (b) Joint angles. (c) Transient responses of E(t) and ||f(t) − r(t)||. (d) Transient responses of ξ(t) and ξ'(t).

The codes are shown in "Supplemented".
