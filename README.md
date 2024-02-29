# Blazor in .NET 8: Sample 13

Blazor is a popular framework for building web applications using C# and .NET. Here are some of the most common and popular third-party Blazor component libraries:

**Telerik UI for Blazor**: Telerik is a well-known name in the .NET community

Their Blazor UI library offers 100+ UI components, including grids, charts, forms, and more. Here's a simple example of using a Telerik button:

@using Telerik.Blazor.Components

<TelerikButton OnClick="@HandleClick">Click me</TelerikButton>

@code {
    void HandleClick()
    {
        Console.WriteLine("Button clicked!");
    }
}

**Syncfusion Blazor**: Syncfusion offers a wide range of Blazor components, including data grids, charts, schedules, and more. Here's an example of using a Syncfusion button:

@using Syncfusion.Blazor.Buttons

<SfButton OnClick="@HandleClick">Click me</SfButton>

@code {
    void HandleClick()
    {
        Console.WriteLine("Button clicked!");
    }
}

**Radzen Blazor**: Radzen offers a variety of Blazor components, including grids, forms, charts, and more. Here's an example of using a Radzen button:

@using Radzen.Blazor

<RadzenButton Click="@HandleClick">Click me</RadzenButton>

@code {
    void HandleClick()
    {
        Console.WriteLine("Button clicked!");
    }
}

**MudBlazor**: MudBlazor is an open-source Material Design component library for Blazor. Here's an example of using a MudBlazor button:

@using MudBlazor

<MudButton OnClick="@HandleClick">Click me</MudButton>

@code {
    void HandleClick()
    {
        Console.WriteLine("Button clicked!");
    }
}
