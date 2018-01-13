<Type Name="ManualScaleSettings" FullName="Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings">
  <TypeSignature Language="C#" Value="public class ManualScaleSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ManualScaleSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class ManualScaleSettings" />
  <TypeSignature Language="F#" Value="type ManualScaleSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0acf1-101">Manuelles Skalieren der Einstellungen für den Cluster.</span><span class="sxs-lookup"><span data-stu-id="0acf1-101">Manual scale settings for the cluster.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManualScaleSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0acf1-102">Initialisiert eine neue Instanz der ManualScaleSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0acf1-102">Initializes a new instance of the ManualScaleSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManualScaleSettings (int targetNodeCount, Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt; nodeDeallocationOption = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 targetNodeCount, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt; nodeDeallocationOption) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings.#ctor(System.Int32,System.Nullable{Microsoft.Azure.Management.BatchAI.Models.DeallocationOption})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (targetNodeCount As Integer, Optional nodeDeallocationOption As Nullable(Of DeallocationOption) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings : int * Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings" Usage="new Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings (targetNodeCount, nodeDeallocationOption)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetNodeCount" Type="System.Int32" />
        <Parameter Name="nodeDeallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt;" />
      </Parameters>
      <Docs>
        <param name="targetNodeCount"><span data-ttu-id="0acf1-103">Die gewünschte Anzahl von Serverknoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="0acf1-103">The desired number of compute nodes in the Cluster.</span></span></param>
        <param name="nodeDeallocationOption"><span data-ttu-id="0acf1-104">Bestimmt, was zu tun, mit der Aufträge auf Serverknoten ausgeführt wird, wenn die Clustergröße abnimmt.</span><span class="sxs-lookup"><span data-stu-id="0acf1-104">Determines what to do with the job(s) running on compute node if the Cluster size is decreasing.</span></span></param>
        <summary>
            <span data-ttu-id="0acf1-105">Initialisiert eine neue Instanz der ManualScaleSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0acf1-105">Initializes a new instance of the ManualScaleSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeDeallocationOption">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt; NodeDeallocationOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt; NodeDeallocationOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings.NodeDeallocationOption" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeDeallocationOption As Nullable(Of DeallocationOption)" />
      <MemberSignature Language="F#" Value="member this.NodeDeallocationOption : Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings.NodeDeallocationOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeDeallocationOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.DeallocationOption&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0acf1-106">Ruft ab oder legt ihn fest bestimmt, wie die Aufträge auf Serverknoten ausgeführt wird, wenn die Clustergröße abnimmt tun.</span><span class="sxs-lookup"><span data-stu-id="0acf1-106">Gets or sets determines what to do with the job(s) running on compute node if the Cluster size is decreasing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0acf1-107">Der Standardwert ist „requeue“.</span><span class="sxs-lookup"><span data-stu-id="0acf1-107">The default value is requeue.</span></span> <span data-ttu-id="0acf1-108">Folgende Werte sind möglich: "wieder in Warteschlange", "Beenden", "Waitforjobcompletion", "unknown"</span><span class="sxs-lookup"><span data-stu-id="0acf1-108">Possible values include: 'requeue', 'terminate', 'waitforjobcompletion', 'unknown'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetNodeCount">
      <MemberSignature Language="C#" Value="public int TargetNodeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 TargetNodeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings.TargetNodeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetNodeCount As Integer" />
      <MemberSignature Language="F#" Value="member this.TargetNodeCount : int with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings.TargetNodeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetNodeCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0acf1-109">Ruft ab oder legt die gewünschte Anzahl von Serverknoten im Cluster.</span><span class="sxs-lookup"><span data-stu-id="0acf1-109">Gets or sets the desired number of compute nodes in the Cluster.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0acf1-110">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="0acf1-110">Default is 0.</span></span> <span data-ttu-id="0acf1-111">Wenn AutoScaleSettings nicht angegeben werden, Start des Clusters mit diesem Ziel.</span><span class="sxs-lookup"><span data-stu-id="0acf1-111">If autoScaleSettings are not specified, then the Cluster starts with this target.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ManualScaleSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="manualScaleSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0acf1-112">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="0acf1-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0acf1-113">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="0acf1-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>