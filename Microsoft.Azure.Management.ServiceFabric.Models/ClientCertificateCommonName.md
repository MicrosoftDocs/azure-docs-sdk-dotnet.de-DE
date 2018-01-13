<Type Name="ClientCertificateCommonName" FullName="Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName">
  <TypeSignature Language="C#" Value="public class ClientCertificateCommonName" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClientCertificateCommonName extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName" />
  <TypeSignature Language="VB.NET" Value="Public Class ClientCertificateCommonName" />
  <TypeSignature Language="F#" Value="type ClientCertificateCommonName = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Client-Zertifikatdetails mithilfe allgemeinen name
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientCertificateCommonName ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ClientCertificateCommonName-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientCertificateCommonName (bool isAdmin, string certificateCommonName, string certificateIssuerThumbprint);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool isAdmin, string certificateCommonName, string certificateIssuerThumbprint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName.#ctor(System.Boolean,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (isAdmin As Boolean, certificateCommonName As String, certificateIssuerThumbprint As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName : bool * string * string -&gt; Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName" Usage="new Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName (isAdmin, certificateCommonName, certificateIssuerThumbprint)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="isAdmin" Type="System.Boolean" />
        <Parameter Name="certificateCommonName" Type="System.String" />
        <Parameter Name="certificateIssuerThumbprint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="isAdmin">Dieses Zertifikat für den Administratorzugriff vom Client verwendet wird, wenn "false", sie verwendet wird oder die Abfrage ist nur zugreifen</param>
        <param name="certificateCommonName">Gemeinsame Zertifikatsname Zugriff gewährt werden; Carefull verwenden allgemeine Namen Platzhalter vorhanden sein</param>
        <param name="certificateIssuerThumbprint">Fingerabdruck des Ausstellers des Zertifikats</param>
        <summary>
            Initialisiert eine neue Instanz der ClientCertificateCommonName-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateCommonName">
      <MemberSignature Language="C#" Value="public string CertificateCommonName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateCommonName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName.CertificateCommonName" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateCommonName As String" />
      <MemberSignature Language="F#" Value="member this.CertificateCommonName : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName.CertificateCommonName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateCommonName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt gemeinsame Zertifikatsname Zugriff gewährt werden. Carefull verwenden allgemeine Namen Platzhalter vorhanden sein
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateIssuerThumbprint">
      <MemberSignature Language="C#" Value="public string CertificateIssuerThumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateIssuerThumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName.CertificateIssuerThumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateIssuerThumbprint As String" />
      <MemberSignature Language="F#" Value="member this.CertificateIssuerThumbprint : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName.CertificateIssuerThumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateIssuerThumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Fingerabdruck des Ausstellers des Zertifikats
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAdmin">
      <MemberSignature Language="C#" Value="public bool IsAdmin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAdmin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName.IsAdmin" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAdmin As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAdmin : bool with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName.IsAdmin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isAdmin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, wird dieses Zertifikat für den Administratorzugriff vom Client verwendet, wenn "false", er wird verwendet, oder Fragen Sie nur Zugriff auf
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="clientCertificateCommonName.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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