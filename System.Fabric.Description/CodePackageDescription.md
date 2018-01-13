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
      <para><span data-ttu-id="e1e81-101">Beschreibt einen Codepaket, das seine Einstiegspunkt enthält.</span><span class="sxs-lookup"><span data-stu-id="e1e81-101">Describes a code package that includes its entry point.</span></span></para>
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
          <para><span data-ttu-id="e1e81-102">Ruft den Einstiegspunkt für das Codepaket.</span><span class="sxs-lookup"><span data-stu-id="e1e81-102">Gets the entry point for the code package.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e1e81-103">Der Einstiegspunkt für das Codepaket.</span><span class="sxs-lookup"><span data-stu-id="e1e81-103">The entry point for the code package.</span></span></para>
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
            <span data-ttu-id="e1e81-104">Ruft ein Flag, das angibt, ob das Codepaket gemeinsam verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="e1e81-104">Gets a flag indicating whether the code package is shared.</span></span>
            </summary>
        <value><span data-ttu-id="e1e81-105">Ein Flag, der angibt, ob das Codepaket freigegeben ist.</span><span class="sxs-lookup"><span data-stu-id="e1e81-105">Flag indicating whether the code package is shared.</span></span></value>
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
          <para><span data-ttu-id="e1e81-106">Ruft den Setup-Einstiegspunkt für das Codepaket.</span><span class="sxs-lookup"><span data-stu-id="e1e81-106">Gets the setup entry point for the code package.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e1e81-107">Der Setup-Einstiegspunkt für das Codepaket.</span><span class="sxs-lookup"><span data-stu-id="e1e81-107">The setup entry point for the code package.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="e1e81-108">Service Fabric bietet Unterstützung für zusätzliche Einstiegspunkt für Entwickler der Anwendung bzw. eines Diensts zu konfigurieren und die Umgebung für ihre Dienste einrichten, ehe der Haupteinstiegspunkt.</span><span class="sxs-lookup"><span data-stu-id="e1e81-108">Service Fabric  provides support for an additional entry point for application/service developers to configure and set up the environment for their services before the main entry point starts.</span></span>  </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>