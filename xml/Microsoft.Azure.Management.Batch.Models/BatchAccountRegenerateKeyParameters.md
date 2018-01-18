<Type Name="BatchAccountRegenerateKeyParameters" FullName="Microsoft.Azure.Management.Batch.Models.BatchAccountRegenerateKeyParameters">
  <TypeSignature Language="C#" Value="public class BatchAccountRegenerateKeyParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchAccountRegenerateKeyParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.BatchAccountRegenerateKeyParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchAccountRegenerateKeyParameters" />
  <TypeSignature Language="F#" Value="type BatchAccountRegenerateKeyParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fa62e-101">Parameter für die RegenerateKey zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="fa62e-101">Parameters supplied to the RegenerateKey operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAccountRegenerateKeyParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.BatchAccountRegenerateKeyParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fa62e-102">Initialisiert eine neue Instanz der BatchAccountRegenerateKeyParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fa62e-102">Initializes a new instance of the BatchAccountRegenerateKeyParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAccountRegenerateKeyParameters (Microsoft.Azure.Management.Batch.Models.AccountKeyType keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Batch.Models.AccountKeyType keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.BatchAccountRegenerateKeyParameters.#ctor(Microsoft.Azure.Management.Batch.Models.AccountKeyType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyName As AccountKeyType)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.BatchAccountRegenerateKeyParameters : Microsoft.Azure.Management.Batch.Models.AccountKeyType -&gt; Microsoft.Azure.Management.Batch.Models.BatchAccountRegenerateKeyParameters" Usage="new Microsoft.Azure.Management.Batch.Models.BatchAccountRegenerateKeyParameters keyName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyName" Type="Microsoft.Azure.Management.Batch.Models.AccountKeyType" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="fa62e-103">Der Typ des kontoschlüssel erneut generiert.</span><span class="sxs-lookup"><span data-stu-id="fa62e-103">The type of account key to regenerate.</span></span>
            <span data-ttu-id="fa62e-104">Folgende Werte sind möglich: 'Primary', 'Sekundären'</span><span class="sxs-lookup"><span data-stu-id="fa62e-104">Possible values include: 'Primary', 'Secondary'</span></span></param>
        <summary>
            <span data-ttu-id="fa62e-105">Initialisiert eine neue Instanz der BatchAccountRegenerateKeyParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fa62e-105">Initializes a new instance of the BatchAccountRegenerateKeyParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.AccountKeyType KeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Models.AccountKeyType KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.BatchAccountRegenerateKeyParameters.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyName As AccountKeyType" />
      <MemberSignature Language="F#" Value="member this.KeyName : Microsoft.Azure.Management.Batch.Models.AccountKeyType with get, set" Usage="Microsoft.Azure.Management.Batch.Models.BatchAccountRegenerateKeyParameters.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.AccountKeyType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fa62e-106">Ruft ab oder legt den Typ des kontoschlüssel erneut generiert.</span><span class="sxs-lookup"><span data-stu-id="fa62e-106">Gets or sets the type of account key to regenerate.</span></span> <span data-ttu-id="fa62e-107">Folgende Werte sind möglich: 'Primary', 'Sekundären'</span><span class="sxs-lookup"><span data-stu-id="fa62e-107">Possible values include: 'Primary', 'Secondary'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.BatchAccountRegenerateKeyParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="batchAccountRegenerateKeyParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fa62e-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="fa62e-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fa62e-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="fa62e-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>