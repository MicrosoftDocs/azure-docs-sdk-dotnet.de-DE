<Type Name="NodeRebootParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.NodeRebootParameter">
  <TypeSignature Language="C#" Value="public class NodeRebootParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeRebootParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.NodeRebootParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeRebootParameter" />
  <TypeSignature Language="F#" Value="type NodeRebootParameter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="aa7c3-101">Optionen für einen Serverknoten neu zu starten.</span><span class="sxs-lookup"><span data-stu-id="aa7c3-101">Options for rebooting a compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeRebootParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeRebootParameter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="aa7c3-102">Initialisiert eine neue Instanz der NodeRebootParameter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="aa7c3-102">Initializes a new instance of the NodeRebootParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeRebootParameter (Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; nodeRebootOption = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; nodeRebootOption) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeRebootParameter.#ctor(System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional nodeRebootOption As Nullable(Of ComputeNodeRebootOption) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.NodeRebootParameter : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.NodeRebootParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.NodeRebootParameter nodeRebootOption" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeRebootOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt;" />
      </Parameters>
      <Docs>
        <param name="nodeRebootOption"><span data-ttu-id="aa7c3-103">Wann Serverknoten neu starten, und was mit den derzeit ausgeführten Tasks geschehen.</span><span class="sxs-lookup"><span data-stu-id="aa7c3-103">When to reboot the compute node and what to do with currently running tasks.</span></span></param>
        <summary>
            <span data-ttu-id="aa7c3-104">Initialisiert eine neue Instanz der NodeRebootParameter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="aa7c3-104">Initializes a new instance of the NodeRebootParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeRebootOption">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; NodeRebootOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; NodeRebootOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeRebootParameter.NodeRebootOption" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeRebootOption As Nullable(Of ComputeNodeRebootOption)" />
      <MemberSignature Language="F#" Value="member this.NodeRebootOption : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeRebootParameter.NodeRebootOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeRebootOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aa7c3-105">Ruft ab oder legt sie fest, wann der Serverknoten neu starten, und was mit den derzeit ausgeführten Tasks geschehen.</span><span class="sxs-lookup"><span data-stu-id="aa7c3-105">Gets or sets when to reboot the compute node and what to do with currently running tasks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="aa7c3-106">Der Standardwert ist „requeue“.</span><span class="sxs-lookup"><span data-stu-id="aa7c3-106">The default value is requeue.</span></span> <span data-ttu-id="aa7c3-107">Folgende Werte sind möglich: "wieder in Warteschlange", "Beenden", "TaskCompletion", "RetainedData"</span><span class="sxs-lookup"><span data-stu-id="aa7c3-107">Possible values include: 'requeue', 'terminate', 'taskCompletion', 'retainedData'</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>