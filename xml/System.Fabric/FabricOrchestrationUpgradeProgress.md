<Type Name="FabricOrchestrationUpgradeProgress" FullName="System.Fabric.FabricOrchestrationUpgradeProgress">
  <TypeSignature Language="C#" Value="public sealed class FabricOrchestrationUpgradeProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FabricOrchestrationUpgradeProgress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricOrchestrationUpgradeProgress" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricOrchestrationUpgradeProgress" />
  <TypeSignature Language="F#" Value="type FabricOrchestrationUpgradeProgress = class" />
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
      <para><span data-ttu-id="fde1f-101">Kapselt den Fortschritt einer Service Fabric-Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="fde1f-101">Encapsulates the progress of a Service Fabric upgrade.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricOrchestrationUpgradeProgress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricOrchestrationUpgradeProgress.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigVersion">
      <MemberSignature Language="C#" Value="public string ConfigVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConfigVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricOrchestrationUpgradeProgress.ConfigVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConfigVersion As String" />
      <MemberSignature Language="F#" Value="member this.ConfigVersion : string" Usage="System.Fabric.FabricOrchestrationUpgradeProgress.ConfigVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fde1f-102">Ruft den JSON-Config-version</span><span class="sxs-lookup"><span data-stu-id="fde1f-102">Gets the JSON config version</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public string Details { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Details" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricOrchestrationUpgradeProgress.Details" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Details As String" />
      <MemberSignature Language="F#" Value="member this.Details : string" Usage="System.Fabric.FabricOrchestrationUpgradeProgress.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fde1f-103">Informationen zum Upgrade</span><span class="sxs-lookup"><span data-stu-id="fde1f-103">Upgrade details</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProgressStatus">
      <MemberSignature Language="C#" Value="public uint ProgressStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int32 ProgressStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricOrchestrationUpgradeProgress.ProgressStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProgressStatus As UInteger" />
      <MemberSignature Language="F#" Value="member this.ProgressStatus : uint32" Usage="System.Fabric.FabricOrchestrationUpgradeProgress.ProgressStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.CLSCompliant(false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.UInt32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="fde1f-104">Ruft den Upgradestatus für dieses Upgrade.</span><span class="sxs-lookup"><span data-stu-id="fde1f-104">Gets the upgrade state for this  upgrade.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="fde1f-105">Der Upgradestatus für dieses Upgrade.</span><span class="sxs-lookup"><span data-stu-id="fde1f-105">The upgrade state for this  upgrade.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeState">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricUpgradeState UpgradeState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.FabricUpgradeState UpgradeState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricOrchestrationUpgradeProgress.UpgradeState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeState As FabricUpgradeState" />
      <MemberSignature Language="F#" Value="member this.UpgradeState : System.Fabric.FabricUpgradeState" Usage="System.Fabric.FabricOrchestrationUpgradeProgress.UpgradeState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricUpgradeState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="fde1f-106">Ruft den Upgradestatus für dieses Upgrade.</span><span class="sxs-lookup"><span data-stu-id="fde1f-106">Gets the upgrade state for this  upgrade.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="fde1f-107">Der Upgradestatus für dieses Upgrade.</span><span class="sxs-lookup"><span data-stu-id="fde1f-107">The upgrade state for this  upgrade.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>