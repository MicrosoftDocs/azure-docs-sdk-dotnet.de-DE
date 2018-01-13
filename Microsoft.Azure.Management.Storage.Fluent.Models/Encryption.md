<Type Name="Encryption" FullName="Microsoft.Azure.Management.Storage.Fluent.Models.Encryption">
  <TypeSignature Language="C#" Value="public class Encryption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi Encryption extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.Models.Encryption" />
  <TypeSignature Language="VB.NET" Value="Public Class Encryption" />
  <TypeSignature Language="F#" Value="type Encryption = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="84c51-101">Die verschlüsselungseinstellungen für das Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="84c51-101">The encryption settings on the storage account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Encryption ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.Encryption.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="84c51-102">Initialisiert eine neue Instanz der Klasse Verschlüsselung an.</span><span class="sxs-lookup"><span data-stu-id="84c51-102">Initializes a new instance of the Encryption class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Encryption (Microsoft.Azure.Management.Storage.Fluent.Models.EncryptionServices services = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Storage.Fluent.Models.EncryptionServices services) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.Encryption.#ctor(Microsoft.Azure.Management.Storage.Fluent.Models.EncryptionServices)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional services As EncryptionServices = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Fluent.Models.Encryption : Microsoft.Azure.Management.Storage.Fluent.Models.EncryptionServices -&gt; Microsoft.Azure.Management.Storage.Fluent.Models.Encryption" Usage="new Microsoft.Azure.Management.Storage.Fluent.Models.Encryption services" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="services" Type="Microsoft.Azure.Management.Storage.Fluent.Models.EncryptionServices" />
      </Parameters>
      <Docs>
        <param name="services"><span data-ttu-id="84c51-103">Liste der Dienste, die Verschlüsselung unterstützt.</span><span class="sxs-lookup"><span data-stu-id="84c51-103">List of services which support encryption.</span></span></param>
        <summary>
            <span data-ttu-id="84c51-104">Initialisiert eine neue Instanz der Klasse Verschlüsselung an.</span><span class="sxs-lookup"><span data-stu-id="84c51-104">Initializes a new instance of the Encryption class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeySource">
      <MemberSignature Language="C#" Value="public static string KeySource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string KeySource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.Encryption.KeySource" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property KeySource As String" />
      <MemberSignature Language="F#" Value="member this.KeySource : string" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.Encryption.KeySource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keySource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="84c51-105">Die Verschlüsselung KeySource (Anbieter).</span><span class="sxs-lookup"><span data-stu-id="84c51-105">The encryption keySource (provider).</span></span> <span data-ttu-id="84c51-106">Mögliche Werte (Groß-/Kleinschreibung): Microsoft.Storage</span><span class="sxs-lookup"><span data-stu-id="84c51-106">Possible values (case-insensitive):  Microsoft.Storage</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Services">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.EncryptionServices Services { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.EncryptionServices Services" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.Encryption.Services" />
      <MemberSignature Language="VB.NET" Value="Public Property Services As EncryptionServices" />
      <MemberSignature Language="F#" Value="member this.Services : Microsoft.Azure.Management.Storage.Fluent.Models.EncryptionServices with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.Encryption.Services" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="services")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.EncryptionServices</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="84c51-107">Ruft ab oder legt die Liste der Dienste, die Verschlüsselung unterstützt.</span><span class="sxs-lookup"><span data-stu-id="84c51-107">Gets or sets list of services which support encryption.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>