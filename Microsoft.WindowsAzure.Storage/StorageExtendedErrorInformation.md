<Type Name="StorageExtendedErrorInformation" FullName="Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation">
  <TypeSignature Language="C#" Value="public sealed class StorageExtendedErrorInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit StorageExtendedErrorInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StorageExtendedErrorInformation" />
  <TypeSignature Language="F#" Value="type StorageExtendedErrorInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt erweiterte Fehlerinformationen, die von Microsoft Azure-Speicherdienste zurückgegeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageExtendedErrorInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalDetails">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; AdditionalDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; AdditionalDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation.AdditionalDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AdditionalDetails As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.AdditionalDetails : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation.AdditionalDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft zusätzliche Fehlerinformationen aus XML-formatierte Eingabestream ab.
            </summary>
        <value>Eine <see cref="T:System.Collections.Generic.IDictionary`2" /> , die die zusätzlichen Fehlerinformationen enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public string ErrorCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As String" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : string" Usage="Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Speicherdienst-Fehlercode ab.
            </summary>
        <value>Eine Zeichenfolge, die die Speicherdienst-Fehlercode enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorMessage">
      <MemberSignature Language="C#" Value="public string ErrorMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation.ErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorMessage As String" />
      <MemberSignature Language="F#" Value="member this.ErrorMessage : string" Usage="Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation.ErrorMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Speicherdienst-Fehlermeldung ab.
            </summary>
        <value>Eine Zeichenfolge, die die Speicherdienst-Fehlermeldung enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadFromStream">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation ReadFromStream (System.IO.Stream inputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation ReadFromStream(class System.IO.Stream inputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation.ReadFromStream(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadFromStream (inputStream As Stream) As StorageExtendedErrorInformation" />
      <MemberSignature Language="F#" Value="static member ReadFromStream : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation" Usage="Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation.ReadFromStream inputStream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="inputStream">Der Eingabestream.</param>
        <summary>
            Ruft die Fehlerdetails aus einem XML-formatierte Fehlermeldung Datenstrom ab.
            </summary>
        <returns>Die Fehlerdetails.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadXml">
      <MemberSignature Language="C#" Value="public void ReadXml (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ReadXml(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation.ReadXml(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReadXml (reader As XmlReader)" />
      <MemberSignature Language="F#" Value="member this.ReadXml : System.Xml.XmlReader -&gt; unit" Usage="storageExtendedErrorInformation.ReadXml reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader">Der <see cref="T:System.Xml.XmlReader" />-Stream, aus dem das <see cref="T:Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation" />-Objekt deserialisiert wird.</param>
        <summary>
            Generiert ein serialisierbares <see cref="T:Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation" /> Objekt aus seiner XML-Darstellung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteXml">
      <MemberSignature Language="C#" Value="public void WriteXml (System.Xml.XmlWriter writer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void WriteXml(class System.Xml.XmlWriter writer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation.WriteXml(System.Xml.XmlWriter)" />
      <MemberSignature Language="VB.NET" Value="Public Sub WriteXml (writer As XmlWriter)" />
      <MemberSignature Language="F#" Value="member this.WriteXml : System.Xml.XmlWriter -&gt; unit" Usage="storageExtendedErrorInformation.WriteXml writer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="System.Xml.XmlWriter" />
      </Parameters>
      <Docs>
        <param name="writer">Die <see cref="T:System.Xml.XmlWriter" /> Datenstrom, in dem die <see cref="T:Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation" /> Objekt serialisiert wird.</param>
        <summary>
            Konvertiert ein serialisierbares <see cref="T:Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation" /> Objekt in seine XML-Darstellung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>