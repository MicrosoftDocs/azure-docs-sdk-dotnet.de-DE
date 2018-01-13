<Type Name="EmailReceiver" FullName="Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver">
  <TypeSignature Language="C#" Value="public class EmailReceiver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EmailReceiver extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver" />
  <TypeSignature Language="VB.NET" Value="Public Class EmailReceiver" />
  <TypeSignature Language="F#" Value="type EmailReceiver = class" />
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
            <span data-ttu-id="a3ad6-101">Ein e-Mail-Empfänger.</span><span class="sxs-lookup"><span data-stu-id="a3ad6-101">An email receiver.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EmailReceiver ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver.#ctor" />
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
            <span data-ttu-id="a3ad6-102">Initialisiert eine neue Instanz der EmailReceiver-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a3ad6-102">Initializes a new instance of the EmailReceiver class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EmailReceiver (string name, string emailAddress, Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt; status = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string emailAddress, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt; status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, emailAddress As String, Optional status As Nullable(Of ReceiverStatus) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver : string * string * Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver (name, emailAddress, status)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="emailAddress" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a3ad6-103">Der Name des e-Mail-Empfänger.</span><span class="sxs-lookup"><span data-stu-id="a3ad6-103">The name of the email receiver.</span></span> <span data-ttu-id="a3ad6-104">Namen müssen über alle Empfänger innerhalb einer Aktivitätsgruppe eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="a3ad6-104">Names must be unique across all receivers within an action group.</span></span></param>
        <param name="emailAddress"><span data-ttu-id="a3ad6-105">Die e-Mail-Adresse von diesem Empfänger.</span><span class="sxs-lookup"><span data-stu-id="a3ad6-105">The email address of this receiver.</span></span></param>
        <param name="status"><span data-ttu-id="a3ad6-106">Der Status der Empfänger der E-mail.</span><span class="sxs-lookup"><span data-stu-id="a3ad6-106">The receiver status of the e-mail.</span></span> <span data-ttu-id="a3ad6-107">Folgende Werte sind möglich: "NotSpecified", "Aktiviert", "Deaktiviert"</span><span class="sxs-lookup"><span data-stu-id="a3ad6-107">Possible values include: 'NotSpecified', 'Enabled', 'Disabled'</span></span></param>
        <summary>
            <span data-ttu-id="a3ad6-108">Initialisiert eine neue Instanz der EmailReceiver-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a3ad6-108">Initializes a new instance of the EmailReceiver class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EmailAddress">
      <MemberSignature Language="C#" Value="public string EmailAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EmailAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver.EmailAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property EmailAddress As String" />
      <MemberSignature Language="F#" Value="member this.EmailAddress : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver.EmailAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="emailAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a3ad6-109">Ruft ab oder legt die e-Mail-Adresse von diesem Empfänger.</span><span class="sxs-lookup"><span data-stu-id="a3ad6-109">Gets or sets the email address of this receiver.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a3ad6-110">Ruft ab oder legt den Namen des e-Mail-Empfängers fest.</span><span class="sxs-lookup"><span data-stu-id="a3ad6-110">Gets or sets the name of the email receiver.</span></span> <span data-ttu-id="a3ad6-111">Namen müssen über alle Empfänger innerhalb einer Aktivitätsgruppe eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="a3ad6-111">Names must be unique across all receivers within an action group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of ReceiverStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ReceiverStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a3ad6-112">Ruft den Status der Empfänger der E-mail ab.</span><span class="sxs-lookup"><span data-stu-id="a3ad6-112">Gets the receiver status of the e-mail.</span></span> <span data-ttu-id="a3ad6-113">Folgende Werte sind möglich: "NotSpecified", "Aktiviert", "Deaktiviert"</span><span class="sxs-lookup"><span data-stu-id="a3ad6-113">Possible values include: 'NotSpecified', 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.EmailReceiver.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="emailReceiver.Validate " />
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
            <span data-ttu-id="a3ad6-114">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="a3ad6-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a3ad6-115">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="a3ad6-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>