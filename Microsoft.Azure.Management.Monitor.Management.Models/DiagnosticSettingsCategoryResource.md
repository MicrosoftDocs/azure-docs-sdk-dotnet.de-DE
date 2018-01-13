<Type Name="DiagnosticSettingsCategoryResource" FullName="Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResource">
  <TypeSignature Language="C#" Value="public class DiagnosticSettingsCategoryResource : Microsoft.Azure.Management.Monitor.Management.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DiagnosticSettingsCategoryResource extends Microsoft.Azure.Management.Monitor.Management.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResource" />
  <TypeSignature Language="VB.NET" Value="Public Class DiagnosticSettingsCategoryResource&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type DiagnosticSettingsCategoryResource = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Monitor.Management.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Die diagnoseeinstellungen Kategorie-Ressource.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiagnosticSettingsCategoryResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResource.#ctor" />
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
            Initialisiert eine neue Instanz der DiagnosticSettingsCategoryResource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiagnosticSettingsCategoryResource (string id = null, string name = null, string type = null, Microsoft.Azure.Management.Monitor.Management.Models.CategoryType categoryType = Microsoft.Azure.Management.Monitor.Management.Models.CategoryType.Metrics);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, valuetype Microsoft.Azure.Management.Monitor.Management.Models.CategoryType categoryType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResource.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.Monitor.Management.Models.CategoryType)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResource : string * string * string * Microsoft.Azure.Management.Monitor.Management.Models.CategoryType -&gt; Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResource" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResource (id, name, type, categoryType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="categoryType" Type="Microsoft.Azure.Management.Monitor.Management.Models.CategoryType" />
      </Parameters>
      <Docs>
        <param name="id">Azure-Ressourcen-Id</param>
        <param name="name">Name des Azure-Ressource</param>
        <param name="type">Azure-Ressourcentyp</param>
        <param name="categoryType">Der Typ der Kategorie diagnoseeinstellungen. Folgende Werte sind möglich: "Metrik", "Protokolle"</param>
        <summary>
            Initialisiert eine neue Instanz der DiagnosticSettingsCategoryResource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CategoryType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.CategoryType CategoryType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Monitor.Management.Models.CategoryType CategoryType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResource.CategoryType" />
      <MemberSignature Language="VB.NET" Value="Public Property CategoryType As CategoryType" />
      <MemberSignature Language="F#" Value="member this.CategoryType : Microsoft.Azure.Management.Monitor.Management.Models.CategoryType with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResource.CategoryType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.categoryType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.CategoryType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ der diagnoseeinstellungen Kategorie fest. Folgende Werte sind möglich: "Metrik", "Protokolle"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>