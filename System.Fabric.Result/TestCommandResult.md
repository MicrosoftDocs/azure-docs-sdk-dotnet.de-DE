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
            Die Basisklasse für der Ergebnisobjekte überprüft.
            </summary>
    <remarks>
            Diese Klasse enthält bedingt die Ausnahme.
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
            Die Basisklasse für andere Test Befehl Ergebnis Klassen ableiten.  Die einzige Eigenschaft in dieser Klasse wird die Ausnahme.
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
            Diese Eigenschaft enthält eine Ausnahme, die den Grund ein Testbefehl fehlerhaft darstellt.  Es ist nicht gültig, es sei denn, die entsprechenden TestCommandProgressState fehlerhaft ist. 
            </summary>
        <value>Das Ausnahmeobjekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>