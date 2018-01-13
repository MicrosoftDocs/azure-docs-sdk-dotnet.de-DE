<Type Name="Application" FullName="Microsoft.Azure.Management.Batch.Models.Application">
  <TypeSignature Language="C#" Value="public class Application" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Application extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.Application" />
  <TypeSignature Language="VB.NET" Value="Public Class Application" />
  <TypeSignature Language="F#" Value="type Application = class" />
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
            Enthält Informationen zu einer Anwendung in einem batchkonto an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Application ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Application.#ctor" />
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
            Initialisiert eine neue Instanz der Anwendung-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Application (string id = null, string displayName = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackage&gt; packages = null, Nullable&lt;bool&gt; allowUpdates = null, string defaultVersion = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string displayName, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.ApplicationPackage&gt; packages, valuetype System.Nullable`1&lt;bool&gt; allowUpdates, string defaultVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Application.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.ApplicationPackage},System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional displayName As String = null, Optional packages As IList(Of ApplicationPackage) = null, Optional allowUpdates As Nullable(Of Boolean) = null, Optional defaultVersion As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.Application : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackage&gt; * Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.Batch.Models.Application" Usage="new Microsoft.Azure.Management.Batch.Models.Application (id, displayName, packages, allowUpdates, defaultVersion)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="packages" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackage&gt;" />
        <Parameter Name="allowUpdates" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="defaultVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Eine Zeichenfolge, die die Anwendung im Konto eindeutig identifiziert.</param>
        <param name="displayName">Der Anzeigename für die Anwendung.</param>
        <param name="packages">Die Liste der Pakete unter dieser Anwendung.</param>
        <param name="allowUpdates">Ein Wert, der angibt, ob die Pakete in der Anwendung unter Verwendung der gleichen Versionszeichenfolge überschrieben werden können.</param>
        <param name="defaultVersion">Das Paket verwenden, wenn ein Client die Anwendung fordert jedoch eine Version nicht angegeben.</param>
        <summary>
            Initialisiert eine neue Instanz der Anwendung-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowUpdates">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AllowUpdates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AllowUpdates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Application.AllowUpdates" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowUpdates As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AllowUpdates : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Application.AllowUpdates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="allowUpdates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, ob die Pakete in der Anwendung unter Verwendung der gleichen Versionszeichenfolge überschrieben werden können.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultVersion">
      <MemberSignature Language="C#" Value="public string DefaultVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Application.DefaultVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultVersion As String" />
      <MemberSignature Language="F#" Value="member this.DefaultVersion : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Application.DefaultVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="defaultVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen des Pakets verwenden, wenn ein Client die Anwendung fordert jedoch eine Version nicht angegeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Application.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Application.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Anzeigenamen für die Anwendung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Application.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Application.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Zeichenfolge, die die Anwendung im Konto eindeutig identifiziert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Packages">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackage&gt; Packages { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.ApplicationPackage&gt; Packages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Application.Packages" />
      <MemberSignature Language="VB.NET" Value="Public Property Packages As IList(Of ApplicationPackage)" />
      <MemberSignature Language="F#" Value="member this.Packages : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackage&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Application.Packages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="packages")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackage&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Pakete unter dieser Anwendung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>