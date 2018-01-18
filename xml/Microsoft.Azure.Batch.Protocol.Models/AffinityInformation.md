<Type Name="AffinityInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.AffinityInformation">
  <TypeSignature Language="C#" Value="public class AffinityInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AffinityInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.AffinityInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class AffinityInformation" />
  <TypeSignature Language="F#" Value="type AffinityInformation = class" />
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
            <span data-ttu-id="187a5-101">Einen ortshinweis an, der vom Batch-Dienst auf einem Serverknoten auf dem eine Aufgabe starten verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="187a5-101">A locality hint that can be used by the Batch service to select a compute node on which to start a task.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AffinityInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AffinityInformation.#ctor" />
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
            <span data-ttu-id="187a5-102">Initialisiert eine neue Instanz der AffinityInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="187a5-102">Initializes a new instance of the AffinityInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AffinityInformation (string affinityId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string affinityId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AffinityInformation.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (affinityId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.AffinityInformation : string -&gt; Microsoft.Azure.Batch.Protocol.Models.AffinityInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.AffinityInformation affinityId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="affinityId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="affinityId"><span data-ttu-id="187a5-103">Eine nicht transparente Zeichenfolge, die den Speicherort der Compute-Knoten oder eine Aufgabe, die zuvor ausgeführten darstellt.</span><span class="sxs-lookup"><span data-stu-id="187a5-103">An opaque string representing the location of a compute node or a task that has run previously.</span></span></param>
        <summary>
            <span data-ttu-id="187a5-104">Initialisiert eine neue Instanz der AffinityInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="187a5-104">Initializes a new instance of the AffinityInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AffinityId">
      <MemberSignature Language="C#" Value="public string AffinityId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AffinityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.AffinityInformation.AffinityId" />
      <MemberSignature Language="VB.NET" Value="Public Property AffinityId As String" />
      <MemberSignature Language="F#" Value="member this.AffinityId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.AffinityInformation.AffinityId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="affinityId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="187a5-105">Ruft ab oder legt eine nicht transparente Zeichenfolge, die den Speicherort der Compute-Knoten oder eine Aufgabe, die zuvor ausgeführten darstellt.</span><span class="sxs-lookup"><span data-stu-id="187a5-105">Gets or sets an opaque string representing the location of a compute node or a task that has run previously.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="187a5-106">Sie können die Affinitäts-ID von einem Serverknoten, um anzugeben, dass diese Aufgabe auf diesem Computeknoten ausgeführt muss, übergeben.</span><span class="sxs-lookup"><span data-stu-id="187a5-106">You can pass the affinityId of a compute node to indicate that this task needs to run on that compute node.</span></span> <span data-ttu-id="187a5-107">Beachten Sie, dass dies nur ein weicher Affinität ist.</span><span class="sxs-lookup"><span data-stu-id="187a5-107">Note that this is just a soft affinity.</span></span> <span data-ttu-id="187a5-108">Wenn der Zielknoten ausgelastet ist oder nicht verfügbar, die zum Zeitpunkt der Task geplant ist, wird die Aufgabe an anderer Stelle geplant werden.</span><span class="sxs-lookup"><span data-stu-id="187a5-108">If the target node is busy or unavailable at the time the task is scheduled, then the task will be scheduled elsewhere.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.AffinityInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="affinityInformation.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="187a5-109">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="187a5-109">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="187a5-110">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="187a5-110">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>