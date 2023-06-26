# 14th

#include<iostream>
#include<vector>
using namespace std;


// 2d - Arrays ()- This is Multidimensional Array
// 2d array - datatype array_name[col][row]
// 3d arrays - 3 {2d array}
// methd to initialize


// int main(){
    
//     // to take input of 2d array
//     int n,m;
//     cin>>n>>m;

//     int array[n][m];

//     for(int i=0;i<n;i++){
//         for(int j=0;j<m;j++){
//             cin>>array[i][j];
//         }
//     }
//     for(int i=0;i<n;i++){
//         for(int j=0;j<m;j++){
//             cout<<array[i][j]<<" ";
//         }
//         cout<<endl;
//     }
//     return 0;
// }

// Q1. Write a program to display multiplication of two matrices entered by the user.

// int main(){
//     int r1,c1;
//     cin>>r1>>c1;

//     int A[r1][c1];// First Array
//     for(int i=0;i<r1;i++){
//         for(int j=0;j<c1;j++){
//             cin>>A[i][j];
//         }
//     }

//     int r2, c2;
//     cin>>r2>>c2;

//     int B[r2][c2];// Second Array
//     for(int i=0;i<r2;i++){
//         for(int j=0;j<c2;j++){
//             cin>>B[i][j];
//         }
//     }

//     if(c1!=r2){
//         cout<<"Matrix multiplication is not Possible for the given array.";

//     }
//     int C[r1][c2];
//     for(int i=0;i<r1;i++){
//         for(int j=0;j<r2;j++){
//             int value=0;
//             for(int k=0;k<r2;k++){
//                 value+=A[i][k]*B[k][j];
//             }
//             C[i][j] = value;
//         }
//     }
//     for(int i=0;i<r1;i++){
//         for(int j=0;j<c2;j++){
//             cout<<C[i][j]<<" ";
//         }cout<<endl;
//     }
//     return 0;
// }



//Q2. To display the transpose of the matrix

int main(){
    int r1,c1;
    cin>>r1>>c1;

    int A[r1][c1];// First Array
    for(int i=0;i<r1;i++){
        for(int j=0;j<c1;j++){
            cin>>A[i][j];
        }
    }
    // Original one 
    for(int i=0;i<r1;i++){
        for(int j=0;j<c1;j++){
            cout<<A[i][j]<<" ";
        }cout<<endl;
    }
    // Transpose one
    for(int i=0;i<c1;i++){
        for(int j=0;j<r1;j++){
            cout<<A[j][i]<<" ";
        }cout<<endl;
    }
    return 0;
}
