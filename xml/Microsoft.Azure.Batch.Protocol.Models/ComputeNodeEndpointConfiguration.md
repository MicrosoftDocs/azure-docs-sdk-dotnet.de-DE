<Type Name="ComputeNodeEndpointConfiguration" FullName="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration">
  <TypeSignature Language="C#" Value="public class ComputeNodeEndpointConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputeNodeEndpointConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputeNodeEndpointConfiguration" />
  <TypeSignature Language="F#" Value="type ComputeNodeEndpointConfiguration = class" />
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
            <span data-ttu-id="7b5a0-101">Die Endpunktkonfiguration für den Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="7b5a0-101">The endpoint configuration for the compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNodeEndpointConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration.#ctor" />
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
            <span data-ttu-id="7b5a0-102">Initialisiert eine neue Instanz der ComputeNodeEndpointConfiguration-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7b5a0-102">Initializes a new instance of the ComputeNodeEndpointConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNodeEndpointConfiguration (System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint&gt; inboundEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint&gt; inboundEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (inboundEndpoints As IList(Of InboundEndpoint))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration" Usage="new Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration inboundEndpoints" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="inboundEndpoints" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint&gt;" />
      </Parameters>
      <Docs>
        <param name="inboundEndpoints"><span data-ttu-id="7b5a0-103">Die Liste der eingehenden Endpunkte, die auf den Computeknoten zugegriffen werden kann.</span><span class="sxs-lookup"><span data-stu-id="7b5a0-103">The list of inbound endpoints that are accessible on the compute node.</span></span></param>
        <summary>
            <span data-ttu-id="7b5a0-104">Initialisiert eine neue Instanz der ComputeNodeEndpointConfiguration-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7b5a0-104">Initializes a new instance of the ComputeNodeEndpointConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InboundEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint&gt; InboundEndpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint&gt; InboundEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration.InboundEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property InboundEndpoints As IList(Of InboundEndpoint)" />
      <MemberSignature Language="F#" Value="member this.InboundEndpoints : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration.InboundEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="inboundEndpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7b5a0-105">Ruft ab oder legt die Liste der eingehenden Endpunkte, die auf den Computeknoten zugegriffen werden kann.</span><span class="sxs-lookup"><span data-stu-id="7b5a0-105">Gets or sets the list of inbound endpoints that are accessible on the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="computeNodeEndpointConfiguration.Validate " />
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
            <span data-ttu-id="7b5a0-106">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="7b5a0-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7b5a0-107">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="7b5a0-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>