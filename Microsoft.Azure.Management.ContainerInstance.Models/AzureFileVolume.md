<Type Name="AzureFileVolume" FullName="Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume">
  <TypeSignature Language="C#" Value="public class AzureFileVolume" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureFileVolume extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureFileVolume" />
  <TypeSignature Language="F#" Value="type AzureFileVolume = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
    <AssemblyVersion>0.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Eigenschaften des Azure-Dateidienst Volumes. Azure-Dateifreigaben werden als Volumes bereitgestellt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureFileVolume ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AzureFileVolume-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureFileVolume (string shareName, string storageAccountName, Nullable&lt;bool&gt; readOnlyProperty = null, string storageAccountKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string shareName, string storageAccountName, valuetype System.Nullable`1&lt;bool&gt; readOnlyProperty, string storageAccountKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume.#ctor(System.String,System.String,System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (shareName As String, storageAccountName As String, Optional readOnlyProperty As Nullable(Of Boolean) = null, Optional storageAccountKey As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume : string * string * Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume" Usage="new Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume (shareName, storageAccountName, readOnlyProperty, storageAccountKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="shareName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="readOnlyProperty" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="storageAccountKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shareName">Der Name der Azure-Dateifreigabe als Volume bereitgestellt werden soll.</param>
        <param name="storageAccountName">Teilen der Namen des Speicherkontos, das Azure-Datei enthält.</param>
        <param name="readOnlyProperty">Das Flag, das angibt, ob die Datei Azure freigegeben wird bereitgestellt, da ein Volume schreibgeschützt ist.</param>
        <param name="storageAccountKey">Der Speicherkonto-Zugriffsschlüssel verwendet, um Zugriff auf die Azure-Dateifreigabe.</param>
        <summary>
            Initialisiert eine neue Instanz der AzureFileVolume-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadOnlyProperty">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ReadOnlyProperty { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ReadOnlyProperty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume.ReadOnlyProperty" />
      <MemberSignature Language="VB.NET" Value="Public Property ReadOnlyProperty As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ReadOnlyProperty : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume.ReadOnlyProperty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="readOnly")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Flag, das angibt, ob die Datei Azure bereitgestellten freigegeben, wie ein Volume schreibgeschützt ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShareName">
      <MemberSignature Language="C#" Value="public string ShareName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ShareName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume.ShareName" />
      <MemberSignature Language="VB.NET" Value="Public Property ShareName As String" />
      <MemberSignature Language="F#" Value="member this.ShareName : string with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume.ShareName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="shareName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen der Azure-Dateifreigabe als Volume bereitgestellt werden soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountKey">
      <MemberSignature Language="C#" Value="public string StorageAccountKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume.StorageAccountKey" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountKey As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountKey : string with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume.StorageAccountKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Speicherkonto-Zugriffsschlüssel verwendet, um Zugriff auf die Azure-Dateifreigabe.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountName">
      <MemberSignature Language="C#" Value="public string StorageAccountName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume.StorageAccountName" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountName As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountName : string with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume.StorageAccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Speicherkontos an, das die Azure-Dateifreigabe enthält.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="azureFileVolume.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>