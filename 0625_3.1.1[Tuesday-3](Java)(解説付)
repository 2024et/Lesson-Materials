[必読(対象者：九九はできているのに正解にならない人向けの話)]
　・各段において一番最初の文字の前には半角2文字分の空白が必要である。
  ・各答えの前後が1桁である場合、半角2文字分の空白が必要であり、二桁同士の時は半角1文字分の空白が必要である。
  つまり...(「*」は空白を意味する)(2の段の場合)
  **2**4**6**8*10*12*14*16*18
  とする必要がある。以上。

public class Main{
    public static void main(String[]args){
        int a, b;
        //なぜか、出力結果を見ると半角で2文字分空白があるため、先に1文字分の半角空白を作っておく。(意味わからん)
        System.out.print(" ");
        //1の段はわざわざ二重ループする必要はないため、そのまま出力。
        for(a=1;a<10;a++){
            System.out.print(" "+a+" ");
        }
        //改行および謎空白の作成。
        System.out.print("\n");
        System.out.print(" ");
        //0倍はないため、a=1から始まり、9までなのでa<10(a<=9でもよい)としたいのだが、本ファイル1行目～6行目に書かれているような謎仕様であるため、答えが2桁になる前にループを止める必要がある。
        for(a=1;a<10;a++){
            for(a=1;a<4;a++){
                b = 2*a;
                System.out.print(" "+b+" ");
            }
            for(a=4;a<10;a++){
                b = 2*a;
                System.out.print(" "+b);
            }
        }
        //0倍はないため、a=1から始まり、9までなのでa<10(a<=9でもよい)としたいのだが、本ファイル1行目～6行目に書かれているような謎仕様であるため、答えが2桁になる前にループを止める必要がある。
        System.out.print("\n");  
        System.out.print(" "); 
        for(a=1;a<10;a++){
            for(a=1;a<3;a++){
                b = 3*a;
                System.out.print(" "+b+" ");
            }
            for(a=3;a<10;a++){
                b = 3*a;
                System.out.print(" "+b);
            }
        }
        //0倍はないため、a=1から始まり、9までなのでa<10(a<=9でもよい)としたいのだが、本ファイル1行目～6行目に書かれているような謎仕様であるため、答えが2桁になる前にループを止める必要がある。
        System.out.print("\n"); 
        System.out.print(" ");  
        for(a=1;a<10;a++){
            for(a=1;a<2;a++){
                b = 4*a;
                System.out.print(" "+b+" ");
            }
            for(a=2;a<10;a++){
                b = 4*a;
                System.out.print(" "+b);
            }
        }
        //ここから先は答えが(1倍の時以外)2桁以上になるので上記のような分割する必要はなく、「普通に」やればよい。
        System.out.print("\n"); 
        System.out.print(" ");  
        for(a=1;a<10;a++){
            for(a=1;a<10;a++){
                b = 5*a;
                System.out.print(" "+b);
            }
        }
        //ここから先は答えが(1倍の時以外)2桁以上になるので上記のような分割する必要はなく、「普通に」やればよい。
        System.out.print("\n"); 
        System.out.print(" ");  
        for(a=1;a<10;a++){
            for(a=1;a<10;a++){
                b = 6*a;
                System.out.print(" "+b);
            }
        }
        System.out.print("\n"); 
        System.out.print(" ");  
        for(a=1;a<10;a++){
            for(a=1;a<10;a++){
                b = 7*a;
                System.out.print(" "+b);
            }
        }
        //ここから先は答えが(1倍の時以外)2桁以上になるので上記のような分割する必要はなく、「普通に」やればよい。
        System.out.print("\n"); 
        System.out.print(" ");  
        for(a=1;a<10;a++){
            for(a=1;a<10;a++){
                b = 8*a;
                System.out.print(" "+b);
            }
        }
        //ここから先は答えが(1倍の時以外)2桁以上になるので上記のような分割する必要はなく、「普通に」やればよい。
        System.out.print("\n");   
        System.out.print(" ");
        for(a=1;a<10;a++){
            for(a=1;a<10;a++){
                b = 9*a;
                System.out.print(" "+b);
            }
        }
    }
}
