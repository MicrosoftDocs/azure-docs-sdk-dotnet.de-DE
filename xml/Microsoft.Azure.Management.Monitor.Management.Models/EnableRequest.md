<Type Name="EnableRequest" FullName="Microsoft.Azure.Management.Monitor.Management.Models.EnableRequest">
  <TypeSignature Language="C#" Value="public class EnableRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EnableRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.EnableRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class EnableRequest" />
  <TypeSignature Language="F#" Value="type EnableRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e970c-101">Beschreibt einen Empfänger, der resubscribed werden soll.</span><span class="sxs-lookup"><span data-stu-id="e970c-101">Describes a receiver that should be resubscribed.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EnableRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.EnableRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e970c-102">Initialisiert eine neue Instanz der EnableRequest-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e970c-102">Initializes a new instance of the EnableRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EnableRequest (string receiverName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string receiverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.EnableRequest.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (receiverName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.EnableRequest : string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.EnableRequest" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.EnableRequest receiverName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="receiverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="receiverName"><span data-ttu-id="e970c-103">Der Name des Empfängers, erneut abonnieren.</span><span class="sxs-lookup"><span data-stu-id="e970c-103">The name of the receiver to resubscribe.</span></span></param>
        <summary>
            <span data-ttu-id="e970c-104">Initialisiert eine neue Instanz der EnableRequest-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e970c-104">Initializes a new instance of the EnableRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiverName">
      <MemberSignature Language="C#" Value="public string ReceiverName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReceiverName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.EnableRequest.ReceiverName" />
      <MemberSignature Language="VB.NET" Value="Public Property ReceiverName As String" />
      <MemberSignature Language="F#" Value="member this.ReceiverName : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.EnableRequest.ReceiverName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="receiverName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e970c-105">Ruft ab oder legt den Namen des Empfängers an erneut abonnieren.</span><span class="sxs-lookup"><span data-stu-id="e970c-105">Gets or sets the name of the receiver to resubscribe.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.EnableRequest.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="enableRequest.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e970c-106">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="e970c-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e970c-107">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="e970c-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>