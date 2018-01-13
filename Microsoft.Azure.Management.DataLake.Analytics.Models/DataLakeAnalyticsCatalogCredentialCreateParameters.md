<Type Name="DataLakeAnalyticsCatalogCredentialCreateParameters" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters">
  <TypeSignature Language="C#" Value="public class DataLakeAnalyticsCatalogCredentialCreateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeAnalyticsCatalogCredentialCreateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeAnalyticsCatalogCredentialCreateParameters" />
  <TypeSignature Language="F#" Value="type DataLakeAnalyticsCatalogCredentialCreateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Data Lake Analytics-Katalog erstellen Anmeldeparameter.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsCatalogCredentialCreateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der DataLakeAnalyticsCatalogCredentialCreateParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsCatalogCredentialCreateParameters (string password, string uri, string userId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string password, string uri, string userId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (password As String, uri As String, userId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters : string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters (password, uri, userId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="uri" Type="System.String" />
        <Parameter Name="userId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="password">das Kennwort für die Anmeldeinformationen und den Benutzer mit Zugriff auf die Datenquelle.</param>
        <param name="uri">Der URI-Bezeichner für die Datenquelle diese Anmeldeinformationen zum Verbinden kann, im Format &lt;Hostname&gt;:&lt;Port&gt;</param>
        <param name="userId">die Objekt-ID für den Benutzer, der diesen Anmeldeinformationen mit Zugriff auf die Datenquelle zugeordnet werden soll.</param>
        <summary>
            Initialisiert eine neue Instanz der DataLakeAnalyticsCatalogCredentialCreateParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Kennwort für die Anmeldeinformationen und den Benutzer mit Zugriff auf die Datenquelle.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public string Uri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters.Uri" />
      <MemberSignature Language="VB.NET" Value="Public Property Uri As String" />
      <MemberSignature Language="F#" Value="member this.Uri : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters.Uri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="uri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Sie in das Format den URI-Bezeichner für die Datenquelle dieser Anmeldeinformationen eine zum Verbindung &amp;Lt; Hostname&amp;Gt;:&amp;Lt; Port&amp;Gt;
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserId">
      <MemberSignature Language="C#" Value="public string UserId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters.UserId" />
      <MemberSignature Language="VB.NET" Value="Public Property UserId As String" />
      <MemberSignature Language="F#" Value="member this.UserId : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters.UserId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="userId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Objekt-ID für den Benutzer, der diesen Anmeldeinformationen mit Zugriff auf die Datenquelle zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="dataLakeAnalyticsCatalogCredentialCreateParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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