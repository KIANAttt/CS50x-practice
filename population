#include <cs50.h>
#include <stdio.h>

int main(void)
{
    int s1; //s1 = start size
    int s2; //s2 = end size

    // TODO: Prompt for start size
    do
    {
        s1 = get_int("Start size");
    }
    while (s1 < 9);

    // TODO: Prompt for end size
    do
    {
        s2 = get_int("End size");
    }
    while (s2 < s1);

    // TODO: Calculate number of years until we reach threshold
    int year = 0;
    while (s1 < s2)
    {
        s1 = s1 + s1/3 - s1/4;
        year++;
    }

    // TODO: Print number of years
    printf("Years: %i", year);
}
