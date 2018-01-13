<Type Name="CheckAvailabilityResult" FullName="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult">
  <TypeSignature Language="C#" Value="public class CheckAvailabilityResult : Microsoft.Azure.Management.NotificationHubs.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CheckAvailabilityResult extends Microsoft.Azure.Management.NotificationHubs.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult" />
  <TypeSignature Language="VB.NET" Value="Public Class CheckAvailabilityResult&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type CheckAvailabilityResult = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.NotificationHubs.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Beschreibung einer CheckAvailibility Ressource.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckAvailabilityResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der CheckAvailabilityResult-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckAvailabilityResult (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.NotificationHubs.Models.Sku sku = null, Nullable&lt;bool&gt; isAvailiable = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.NotificationHubs.Models.Sku sku, valuetype System.Nullable`1&lt;bool&gt; isAvailiable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.NotificationHubs.Models.Sku,System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.NotificationHubs.Models.Sku * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult" Usage="new Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult (location, id, name, type, tags, sku, isAvailiable)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.NotificationHubs.Models.Sku" />
        <Parameter Name="isAvailiable" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="location">Speicherort von Ressourcen</param>
        <param name="id">Ressourcen-Id</param>
        <param name="name">Ressourcenname</param>
        <param name="type">Ressourcentyp</param>
        <param name="tags">Ressourcentags</param>
        <param name="sku">Die Sku des erstellten namespace</param>
        <param name="isAvailiable">"True", wenn der Name verfügbar ist, und kann zum Erstellen von neuen Namespace/NotificationHub verwendet werden. Andernfalls "false".</param>
        <summary>
            Initialisiert eine neue Instanz der CheckAvailabilityResult-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAvailiable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsAvailiable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsAvailiable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult.IsAvailiable" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAvailiable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsAvailiable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult.IsAvailiable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isAvailiable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt "true", wenn der Name verfügbar ist und kann zum Erstellen von neuen Namespace/NotificationHub verwendet werden. Andernfalls "false".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>