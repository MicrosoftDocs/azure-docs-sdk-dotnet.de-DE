<Type Name="ConsumerGroup" FullName="Microsoft.Azure.Management.EventHub.Models.ConsumerGroup">
  <TypeSignature Language="C#" Value="public class ConsumerGroup : Microsoft.Azure.Management.EventHub.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConsumerGroup extends Microsoft.Azure.Management.EventHub.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventHub.Models.ConsumerGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class ConsumerGroup&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ConsumerGroup = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.EventHub.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Einzelnes Element im Vorgang "Gruppe" Liste "oder" Get-Consumer
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConsumerGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.Models.ConsumerGroup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ConsumerGroup-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConsumerGroup (string id = null, string name = null, string type = null, Nullable&lt;DateTime&gt; createdAt = null, Nullable&lt;DateTime&gt; updatedAt = null, string userMetadata = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdAt, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; updatedAt, string userMetadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.Models.ConsumerGroup.#ctor(System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional createdAt As Nullable(Of DateTime) = null, Optional updatedAt As Nullable(Of DateTime) = null, Optional userMetadata As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventHub.Models.ConsumerGroup : string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.Management.EventHub.Models.ConsumerGroup" Usage="new Microsoft.Azure.Management.EventHub.Models.ConsumerGroup (id, name, type, createdAt, updatedAt, userMetadata)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="createdAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="updatedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="userMetadata" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-Id</param>
        <param name="name">Ressourcenname</param>
        <param name="type">Ressourcentyp</param>
        <param name="createdAt">Genaue Uhrzeit der Erstellung der Nachrichteninhalts.</param>
        <param name="updatedAt">Die genaue Uhrzeit wurde die Nachricht aktualisiert.</param>
        <param name="userMetadata">Usermetadata ist ein Platzhalter zum Speichern von Zeichenfolgendaten mit maximal 1024. z. B. dienen zum Speichern von beschreibender Daten, z. B. die Liste der Teams und die entsprechenden Kontaktinformationen finden auch eine benutzerdefinierte Konfigurationseinstellungen gespeichert werden können.</param>
        <summary>
            Initialisiert eine neue Instanz der ConsumerGroup-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.ConsumerGroup.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.EventHub.Models.ConsumerGroup.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createdAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die genaue Uhrzeit der Erstellung die Nachricht ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.ConsumerGroup.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.EventHub.Models.ConsumerGroup.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.updatedAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die genaue Uhrzeit, an die Nachricht aktualisiert wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserMetadata">
      <MemberSignature Language="C#" Value="public string UserMetadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserMetadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.ConsumerGroup.UserMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Property UserMetadata As String" />
      <MemberSignature Language="F#" Value="member this.UserMetadata : string with get, set" Usage="Microsoft.Azure.Management.EventHub.Models.ConsumerGroup.UserMetadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.userMetadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Usermetadata ist ein Platzhalter zum Speichern von Zeichenfolgendaten mit maximal 1024. z. B. dienen zum Speichern von beschreibender Daten, z. B. die Liste der Teams und die entsprechenden Kontaktinformationen finden auch eine benutzerdefinierte Konfigurationseinstellungen gespeichert werden können.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>