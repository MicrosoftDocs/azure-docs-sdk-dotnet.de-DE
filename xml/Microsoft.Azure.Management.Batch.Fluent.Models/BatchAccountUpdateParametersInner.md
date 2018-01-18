<Type Name="BatchAccountUpdateParametersInner" FullName="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner">
  <TypeSignature Language="C#" Value="public class BatchAccountUpdateParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchAccountUpdateParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchAccountUpdateParametersInner" />
  <TypeSignature Language="F#" Value="type BatchAccountUpdateParametersInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="27039-101">Parameter, die auf den Updatevorgang angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="27039-101">Parameters supplied to the Update operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAccountUpdateParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="27039-102">Initialisiert eine neue Instanz der BatchAccountUpdateParametersInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="27039-102">Initializes a new instance of the BatchAccountUpdateParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchAccountUpdateParametersInner (System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageBaseProperties autoStorage = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageBaseProperties autoStorage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner.#ctor(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageBaseProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional tags As IDictionary(Of String, String) = null, Optional autoStorage As AutoStorageBaseProperties = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageBaseProperties -&gt; Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner" Usage="new Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner (tags, autoStorage)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="autoStorage" Type="Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageBaseProperties" />
      </Parameters>
      <Docs>
        <param name="tags"><span data-ttu-id="27039-103">Der benutzerdefinierte Tags, die dem Konto zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="27039-103">The user specified tags associated with the account.</span></span></param>
        <param name="autoStorage"><span data-ttu-id="27039-104">Die Eigenschaften im Zusammenhang mit Auto-Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="27039-104">The properties related to auto storage account.</span></span></param>
        <summary>
            <span data-ttu-id="27039-105">Initialisiert eine neue Instanz der BatchAccountUpdateParametersInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="27039-105">Initializes a new instance of the BatchAccountUpdateParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoStorage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageBaseProperties AutoStorage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageBaseProperties AutoStorage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner.AutoStorage" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoStorage As AutoStorageBaseProperties" />
      <MemberSignature Language="F#" Value="member this.AutoStorage : Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageBaseProperties with get, set" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner.AutoStorage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoStorage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Models.AutoStorageBaseProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="27039-106">Ruft ab oder legt die Eigenschaften im Zusammenhang mit der automatischen Storage-Konto fest.</span><span class="sxs-lookup"><span data-stu-id="27039-106">Gets or sets the properties related to auto storage account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="27039-107">Ruft ab oder legt fest, die der benutzerdefinierte Tags, die dem Konto zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="27039-107">Gets or sets the user specified tags associated with the account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Models.BatchAccountUpdateParametersInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="batchAccountUpdateParametersInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="27039-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="27039-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="27039-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="27039-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>