<Type Name="ResourceManagementErrorWithDetails" FullName="Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails">
  <TypeSignature Language="C#" Value="public class ResourceManagementErrorWithDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceManagementErrorWithDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceManagementErrorWithDetails" />
  <TypeSignature Language="F#" Value="type ResourceManagementErrorWithDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die ausführliche Fehlermeldung der ressourcenverwaltung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceManagementErrorWithDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ResourceManagementErrorWithDetails-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceManagementErrorWithDetails (string code = null, string message = null, string target = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails&gt; details = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, string message, string target, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails&gt; details) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails.#ctor(System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As String = null, Optional message As String = null, Optional target As String = null, Optional details As IList(Of ResourceManagementErrorWithDetails) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails : string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails (code, message, target, details)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="target" Type="System.String" />
        <Parameter Name="details" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails&gt;" />
      </Parameters>
      <Docs>
        <param name="code">Der Fehlercode zurückgegeben, wenn die Vorlage zu exportieren.</param>
        <param name="message">Die Fehlermeldung, die Beschreibung des Fehlers exportieren.</param>
        <param name="target">Das Ziel des Fehlers.</param>
        <param name="details">Validierungsfehler.</param>
        <summary>
            Initialisiert eine neue Instanz der ResourceManagementErrorWithDetails-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails.Code" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den beim Exportieren der Vorlage zurückgegebenen Fehlercode ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails&gt; Details { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails&gt; Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails.Details" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Details As IList(Of ResourceManagementErrorWithDetails)" />
      <MemberSignature Language="F#" Value="member this.Details : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Validierungsfehler ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Beschreibung des Fehlers Export Fehlermeldung ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Target">
      <MemberSignature Language="C#" Value="public string Target { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Target" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails.Target" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Target As String" />
      <MemberSignature Language="F#" Value="member this.Target : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails.Target" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="target")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Ziel des Fehlers ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>