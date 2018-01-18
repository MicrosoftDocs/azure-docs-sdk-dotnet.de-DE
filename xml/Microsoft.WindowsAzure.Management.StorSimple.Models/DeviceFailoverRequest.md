<Type Name="DeviceFailoverRequest" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest">
  <TypeSignature Language="C#" Value="public class DeviceFailoverRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeviceFailoverRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class DeviceFailoverRequest" />
  <TypeSignature Language="F#" Value="type DeviceFailoverRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="63ace-101">Stellt eine Anforderung für ein Failover eines Geräts.</span><span class="sxs-lookup"><span data-stu-id="63ace-101">Represents a request to failover a device.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceFailoverRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="63ace-102">Initialisiert eine neue Instanz der DeviceFailoverRequest-Klasse.</span><span class="sxs-lookup"><span data-stu-id="63ace-102">Initializes a new instance of the DeviceFailoverRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeviceFailoverRequest (System.Collections.Generic.List&lt;string&gt; dataContainerIds, string targetDeviceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.List`1&lt;string&gt; dataContainerIds, string targetDeviceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest.#ctor(System.Collections.Generic.List{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (dataContainerIds As List(Of String), targetDeviceId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest : System.Collections.Generic.List&lt;string&gt; * string -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest" Usage="new Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest (dataContainerIds, targetDeviceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dataContainerIds" Type="System.Collections.Generic.List&lt;System.String&gt;" />
        <Parameter Name="targetDeviceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="dataContainerIds">To be added.</param>
        <param name="targetDeviceId">To be added.</param>
        <summary>
            <span data-ttu-id="63ace-103">Initialisiert eine neue Instanz der DeviceFailoverRequest-Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="63ace-103">Initializes a new instance of the DeviceFailoverRequest class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CleanupPrimary">
      <MemberSignature Language="C#" Value="public bool CleanupPrimary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CleanupPrimary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest.CleanupPrimary" />
      <MemberSignature Language="VB.NET" Value="Public Property CleanupPrimary As Boolean" />
      <MemberSignature Language="F#" Value="member this.CleanupPrimary : bool with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest.CleanupPrimary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="63ace-104">Optional.</span><span class="sxs-lookup"><span data-stu-id="63ace-104">Optional.</span></span> <span data-ttu-id="63ace-105">Flag, das angibt, ob das Cleanup primäres Gerät</span><span class="sxs-lookup"><span data-stu-id="63ace-105">Flag indicating whether to cleanup the primary device</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataContainerIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DataContainerIds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DataContainerIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest.DataContainerIds" />
      <MemberSignature Language="VB.NET" Value="Public Property DataContainerIds As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DataContainerIds : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest.DataContainerIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="63ace-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="63ace-106">Required.</span></span> <span data-ttu-id="63ace-107">Die Liste der Container-Ids für Failover</span><span class="sxs-lookup"><span data-stu-id="63ace-107">The list of data container ids to failover</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReturnWorkflowId">
      <MemberSignature Language="C#" Value="public bool ReturnWorkflowId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ReturnWorkflowId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest.ReturnWorkflowId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReturnWorkflowId As Boolean" />
      <MemberSignature Language="F#" Value="member this.ReturnWorkflowId : bool with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest.ReturnWorkflowId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="63ace-108">Optional.</span><span class="sxs-lookup"><span data-stu-id="63ace-108">Optional.</span></span> <span data-ttu-id="63ace-109">Flag, das angibt, ob die Workflow-Id zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="63ace-109">Flag indicating whether to return the workflow id</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDeviceId">
      <MemberSignature Language="C#" Value="public string TargetDeviceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetDeviceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest.TargetDeviceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDeviceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetDeviceId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest.TargetDeviceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="63ace-110">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="63ace-110">Required.</span></span> <span data-ttu-id="63ace-111">Der Ziel-Geräte-ID.</span><span class="sxs-lookup"><span data-stu-id="63ace-111">The target device identifier</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>