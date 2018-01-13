<Type Name="ReentrancyModeDisallowedException" FullName="Microsoft.ServiceFabric.Actors.ReentrancyModeDisallowedException">
  <TypeSignature Language="C#" Value="public sealed class ReentrancyModeDisallowedException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit ReentrancyModeDisallowedException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.ReentrancyModeDisallowedException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReentrancyModeDisallowedException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type ReentrancyModeDisallowedException = class&#xA;    inherit FabricException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.FabricException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Ausnahme, die vom Akteur-Laufzeit ausgelöst, wenn der reentrant-Aufruf für einen Akteur ausgeführt wird und die zugehörige <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode" /> festgelegt ist, um <see cref="F:Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode.Disallowed" />.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReentrancyModeDisallowedException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ReentrancyModeDisallowedException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceFabric.Actors.ReentrancyModeDisallowedException" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReentrancyModeDisallowedException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ReentrancyModeDisallowedException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.ReentrancyModeDisallowedException : string -&gt; Microsoft.ServiceFabric.Actors.ReentrancyModeDisallowedException" Usage="new Microsoft.ServiceFabric.Actors.ReentrancyModeDisallowedException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceFabric.Actors.ReentrancyModeDisallowedException" />-Klasse mit einer angegebenen Fehlermeldung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReentrancyModeDisallowedException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ReentrancyModeDisallowedException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.ReentrancyModeDisallowedException : string * Exception -&gt; Microsoft.ServiceFabric.Actors.ReentrancyModeDisallowedException" Usage="new Microsoft.ServiceFabric.Actors.ReentrancyModeDisallowedException (message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</param>
        <param name="inner">Die Ausnahme, die die Ursache für die aktuelle Ausnahme oder ein null-Verweis ist, wenn keine innere Ausnahme angegeben wird.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceFabric.Actors.ReentrancyModeDisallowedException" />-Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>