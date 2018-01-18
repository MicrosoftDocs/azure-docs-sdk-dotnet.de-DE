<Type Name="TestCommandResult" FullName="System.Fabric.Result.TestCommandResult">
  <TypeSignature Language="C#" Value="public abstract class TestCommandResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract serializable beforefieldinit TestCommandResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Result.TestCommandResult" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TestCommandResult" />
  <TypeSignature Language="F#" Value="type TestCommandResult = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="92a3f-101">Die Basisklasse für der Ergebnisobjekte überprüft.</span><span class="sxs-lookup"><span data-stu-id="92a3f-101">Base class for the result objects.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="92a3f-102">Diese Klasse enthält bedingt die Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="92a3f-102">This class conditionally contains the Exception</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TestCommandResult ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Result.TestCommandResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="92a3f-103">Die Basisklasse für andere Test Befehl Ergebnis Klassen ableiten.</span><span class="sxs-lookup"><span data-stu-id="92a3f-103">The base class for other test command result classes to derive from.</span></span>  <span data-ttu-id="92a3f-104">Die einzige Eigenschaft in dieser Klasse wird die Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="92a3f-104">The only property in this class is Exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.TestCommandResult.Exception" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception" Usage="System.Fabric.Result.TestCommandResult.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92a3f-105">Diese Eigenschaft enthält eine Ausnahme, die den Grund ein Testbefehl fehlerhaft darstellt.</span><span class="sxs-lookup"><span data-stu-id="92a3f-105">This property contains an exception representing the reason a test command faulted.</span></span>  <span data-ttu-id="92a3f-106">Es ist nicht gültig, es sei denn, die entsprechenden TestCommandProgressState fehlerhaft ist.</span><span class="sxs-lookup"><span data-stu-id="92a3f-106">It is not valid unless the corresponding TestCommandProgressState is Faulted.</span></span> 
            </summary>
        <value><span data-ttu-id="92a3f-107">Das Ausnahmeobjekt.</span><span class="sxs-lookup"><span data-stu-id="92a3f-107">The Exception object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>