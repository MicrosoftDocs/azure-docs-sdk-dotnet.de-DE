<Type Name="CodePackageDescription" FullName="System.Fabric.Description.CodePackageDescription">
  <TypeSignature Language="C#" Value="public sealed class CodePackageDescription : System.Fabric.Description.PackageDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CodePackageDescription extends System.Fabric.Description.PackageDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.CodePackageDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CodePackageDescription&#xA;Inherits PackageDescription" />
  <TypeSignature Language="F#" Value="type CodePackageDescription = class&#xA;    inherit PackageDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.PackageDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Beschreibt einen Codepaket, das seine Einstiegspunkt enthält.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EntryPoint">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.EntryPointDescription EntryPoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.EntryPointDescription EntryPoint" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.CodePackageDescription.EntryPoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EntryPoint As EntryPointDescription" />
      <MemberSignature Language="F#" Value="member this.EntryPoint : System.Fabric.Description.EntryPointDescription" Usage="System.Fabric.Description.CodePackageDescription.EntryPoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.EntryPointDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Einstiegspunkt für das Codepaket.</para>
        </summary>
        <value>
          <para>Der Einstiegspunkt für das Codepaket.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsShared">
      <MemberSignature Language="C#" Value="public bool IsShared { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsShared" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.CodePackageDescription.IsShared" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsShared As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsShared : bool" Usage="System.Fabric.Description.CodePackageDescription.IsShared" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ein Flag, das angibt, ob das Codepaket gemeinsam verwendet wird.
            </summary>
        <value>Ein Flag, der angibt, ob das Codepaket freigegeben ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetupEntryPoint">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ExeHostEntryPointDescription SetupEntryPoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.ExeHostEntryPointDescription SetupEntryPoint" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.CodePackageDescription.SetupEntryPoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SetupEntryPoint As ExeHostEntryPointDescription" />
      <MemberSignature Language="F#" Value="member this.SetupEntryPoint : System.Fabric.Description.ExeHostEntryPointDescription" Usage="System.Fabric.Description.CodePackageDescription.SetupEntryPoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ExeHostEntryPointDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Setup-Einstiegspunkt für das Codepaket.</para>
        </summary>
        <value>
          <para>Der Setup-Einstiegspunkt für das Codepaket.</para>
        </value>
        <remarks>
          <para>Service Fabric bietet Unterstützung für zusätzliche Einstiegspunkt für Entwickler der Anwendung bzw. eines Diensts zu konfigurieren und die Umgebung für ihre Dienste einrichten, ehe der Haupteinstiegspunkt.  </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>