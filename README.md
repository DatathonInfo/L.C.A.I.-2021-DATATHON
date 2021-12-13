# L.C.A.I. 2021 DATATHON
후두내시경 이미지의 AI 학습데이터를 이용한 데이터톤 


![a2포스터_인쇄용_201217_outline_대지 1 사본 2](https://user-images.githubusercontent.com/92664643/144184224-a71c9de1-b4fc-46f2-b63f-92f369b51d2b.png)



L.C.A.I. 2021은 ‘2021 인공지능 학습용 데이터 구축사업’을 통해 만들어진 후두내시경 학습용 데이터를 활용하여 후두 종양을 효과적으로 예측할 수 있는가에 대한 AI 모델링 챌린지입니다.

본 대회는 NAVER CLOUD PLATFORM의 고성능 클라우드 인프라 상에서 운영되며 네이버의 클라우드 플랫폼<strong>[NAVER CLOUD PLATFORM](https://www.ncloud.com/)</strong>에서 개발자들이 "모델 개발과 알고리즘 최적화"에만 집중할 수 있도록 필요한 제반 환경을 제공합니다. 
AI 전문가들과 함께 인공지능 모델 개발에 도전하실 분들을 기다리고 있습니다.


## 챌린지
> 후두내시경 데이터를 이용하여 후두암 발생을 예측하는 인공지능 모델 개발 <br>


## 시상 및 혜택
>- 총상금: 추후 공개  <br>
<table class="tbl_prize">
  <tr>
    <th style="text-align:left;width:50%">구분</th>
    <th style="text-align:center;width:15%">시상</th>
        <th style="text-align:left;width:35%">상금</th>
  </tr>
  <tr>
    <td align=center>
      <strong> 1위 </strong><br>
    </td>
    <td align=center> 대상 (1팀) </td>
    <td>  300만원 </td>
  </tr>
    <tr>
    <td align=center>
      <strong> 2위 </strong><br>
    </td>
    <td align=center> 최우수상 (1팀) </td>
        <td align=center> 150만원 </td>
   </tr>
      <tr>
    <td align=center>
      <strong> 3위 </strong><br>
    </td>
    <td align=center> 우수상 (1팀) </td>
        <td align=center>  50만원 </td>
   </tr>
</table>

## 대회 일정
<table class="tbl_schedule">
  <tr>
    <th style="text-align:left;width:50%">행사내용</th>
    <th style="text-align:center;width:15%">일정</th>
        <th style="text-align:left;width:35%">장소/방식</th>
  </tr>
  <tr>
    <td align=center>
      <strong>참가 신청</strong><br>
    </td>
    <td align=center> 2021년 11월 29일 ~ 12월 9일</td>
    <td align=center> 온라인
 </td>
  </tr>
    <tr>
    <td align=center>
            <strong>개회식 및 설명회</strong><br>
    </td>
    <td align=center> 2021년 12월 13일 14:00~ </td>
    <td align=center> 온라인 공지 </td>
  </tr>
    <tr>
    <td align=center>      
             <strong>대회</strong><br>
    </td>
    <td align=center> 2021년 12월 13일 14:00 ~ 12월 15일 14:00 </td>
    <td align=center> 온라인 </td>
  </tr>
  </table>
  
  <span style="color:red">대회기간 이후에는 서버 접속이 불가능합니다.</span>

## 심사기준
- 서면평가: 참가신청서, 참가팀 역량 (예선 진출팀 5개 팀 선발)
- 대회: 종료 시점 후 제출된 결과요약지와 개발 모델 제출 
>   제출 내용: 학습코드, 모델 Weight, 환경, 모델설명 1GB 미만
>   
>   필수 제출 파일 : 총 3개  
>   
>                   모델 1. 테스트 코드와 모델 > 압축 파일명 : 팀명_LCAI2021.h5/pth/py  
>   
>                   결과요약지 1. 첨부파일 참고 > PDF 파일명 : 팀명_LCAI2021_결과요약지.pdf
>                    
>                   PNG mask 1.  압축 파일 > 압축 파일명 : 팀명__LCAI2021_PNG_mask.zip
>
>    제출 : datathon2021info@gmail.com
>                   
*모델 사이즈 제한 1GB 미만 <br>

*동점자 발생 시 모델 제출 시간이 빠른 순서, 모델 크기가 작은 순서 순으로 우선순위 결정 <br>
  
## 참가신청
1. 신청 기간: 2021년 11월 29일 ~ 12월 9일 <br>
2. 신청 방법: [온라인](www.lcaidatathon.com)

### Github 게시판
* **온라인 Issues 게시판 대회기간 중 10:00~19:00 운영**

### 대회참가 시 주의사항 

본 대회에서는 팀당 P40(2GPU), GPU 메모리 48GB, 8vCPU, 메모리 60GB 서버가 제공됩니다. 
본 서버 이용에 있어 서버 환경 설정 시 Kernel 업데이트를 할 경우 정상적인 이용이 어려울 수 있으므로
Kernel 업데이트를 진행하시지 않기를 권장드립니다.

>*Kernel 업데이트로 인한 팀별 서버 다운 및 복구 시간 소요에 대해서는 별도의 복구는 지원되지 않으니 각별히 유의해주시기 바랍니다.

서버에 세팅된 OS 및 개발 환경 정보

- CentOS 7.8
- Anaconda3-5.3.1
- Python 3.7
- CUDA 10.0
- cuDNN 7.6.0


현재 각 팀별 서버는 위와 같은 사양으로 테스트 및 세팅되어 있습니다.
대회 참여 시 참고하시고, 별도의 세팅 지원은 어려울 수 있으니 양해부탁드립니다. 
