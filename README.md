# protocol



#import <Foundation/Foundation.h>
#import "marryProcol.h"
@interface girl : NSObject
{
    NSString *_name;
    NSInteger _age;
    
    id<marryProcol> _delegate;
    
}

-(void)setDelegate:(id<marryProcol>)husband;

-(id<marryProcol>)getDelegate;


-(id)initWithName:(NSString *)name age:(NSInteger)age;

-(void)setName:(NSString *)name;

-(void)setAge:(NSInteger)age;

-(NSString *)getName;

-(NSInteger)getAge;

-(void)wantEat;

-(void)wantMoney;

-(void)wantCar;

-(void)wantHouse;

@end
