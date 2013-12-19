#include <iostream>
#include <cstdlib>
#include <ctime>
using namespace  std;

int main()
{
    int math[4], chinese[4], english[4];//三個科目都設定陣列 裡面放四個位置 第零個位置不要用（怕混淆）
    int total1=0,total2=0,total3=0;
    double averageMath,averageChinese,averageEnglish;
    srand(time(NULL));
    math[1]=rand()%101;//隨機產生各科的變數 範圍為0~100
    math[2]=rand()%101;
    math[3]=rand()%101;
    
    chinese[1]=rand()%101;
    chinese[2]=rand()%101;
    chinese[3]=rand()%101;
    
    english[1]=rand()%101;
    english[2]=rand()%101;
    english[3]=rand()%101;
    
    averageMath=(math[1]+math[2]+math[3])/3;//算個科平均
    averageChinese=(chinese[1]+chinese[2]+chinese[3])/3;
    averageEnglish=(english[1]+english[2]+english[3])/3;
    
    
    cout<<"First student Math score: "<<math[1]<<endl;
    cout<<"First student Chinese score: "<<chinese[1]<<endl;
    cout<<"First student English score: "<<english[1]<<endl;
    cout<<"First student total score: "<< (math[1]+chinese[1]+english[1]) <<endl ;
    
    cout<<"Second student Math score: "<<math[2]<<endl;
    cout<<"Second student Chinese score: "<<chinese[2]<<endl;
    cout<<"Second student English score: "<<english[2]<<endl;
    cout<<"Second student total score: "<< (math[2]+chinese[2]+english[2]) <<endl ;
    
    cout<<"Third student Math score: "<<math[3]<<endl;
    cout<<"Third student Chinese score: "<<chinese[3]<<endl;
    cout<<"Third student English score: "<<english[3]<<endl;
    cout<<"Third student total score: "<< (math[3]+chinese[3]+english[3]) <<endl ;
    
    cout<<"Math average score: "<< averageMath <<endl ;
    cout<<"Chinese average score: "<<averageChinese <<endl ;
    cout<<"English average score: "<< averageEnglish <<endl;
    
    return 0;
    
    
}
