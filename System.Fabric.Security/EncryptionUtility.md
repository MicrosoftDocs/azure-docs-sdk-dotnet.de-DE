<Type Name="EncryptionUtility" FullName="System.Fabric.Security.EncryptionUtility">
  <TypeSignature Language="C#" Value="public sealed class EncryptionUtility" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EncryptionUtility extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Security.EncryptionUtility" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EncryptionUtility" />
  <TypeSignature Language="F#" Value="type EncryptionUtility = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt die Encryption-Hilfsprogramm dar.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionUtility ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Instanziiert eine neue <see cref="T:System.Fabric.Security.EncryptionUtility" /> Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DecryptText">
      <MemberSignature Language="C#" Value="public static System.Security.SecureString DecryptText (string textToDecrypt);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Security.SecureString DecryptText(string textToDecrypt) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.DecryptText(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DecryptText (textToDecrypt As String) As SecureString" />
      <MemberSignature Language="F#" Value="static member DecryptText : string -&gt; System.Security.SecureString" Usage="System.Fabric.Security.EncryptionUtility.DecryptText textToDecrypt" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.SecureString</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="textToDecrypt" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="textToDecrypt">
          <para>Der verschlüsselte Text entschlüsselt.</para>
        </param>
        <summary>
          <para>Entschlüsseln Sie eine Textzeichenfolge, die von Methoden EncryptText verschlüsselt <see cref="T:System.Fabric.Security.EncryptionUtility" />, es wird davon ausgegangen, dass der Speicherort des Entschlüsselungszertifikats LocalMachine ist.</para>
        </summary>
        <returns>
          <para>Der verschlüsselte Text als <see cref="T:System.Security.SecureString" />.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DecryptText">
      <MemberSignature Language="C#" Value="public static System.Security.SecureString DecryptText (string textToDecrypt, System.Security.Cryptography.X509Certificates.StoreLocation storeLocation);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Security.SecureString DecryptText(string textToDecrypt, valuetype System.Security.Cryptography.X509Certificates.StoreLocation storeLocation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.DecryptText(System.String,System.Security.Cryptography.X509Certificates.StoreLocation)" />
      <MemberSignature Language="F#" Value="static member DecryptText : string * System.Security.Cryptography.X509Certificates.StoreLocation -&gt; System.Security.SecureString" Usage="System.Fabric.Security.EncryptionUtility.DecryptText (textToDecrypt, storeLocation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.SecureString</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="textToDecrypt" Type="System.String" />
        <Parameter Name="storeLocation" Type="System.Security.Cryptography.X509Certificates.StoreLocation" />
      </Parameters>
      <Docs>
        <param name="textToDecrypt">
          <para>Der verschlüsselte Text entschlüsselt.</para>
        </param>
        <param name="storeLocation">
          <para>Das Zertifikat-Speicherort Entschlüsselungszertifikat abgerufen.</para>
        </param>
        <summary>
          <para>Entschlüsseln Sie eine Textzeichenfolge, die von Methoden EncryptText verschlüsselt <see cref="T:System.Fabric.Security.EncryptionUtility" />.</para>
        </summary>
        <returns>
          <para>Der verschlüsselte Text als <see cref="T:System.Security.SecureString" />.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DecryptValue">
      <MemberSignature Language="C#" Value="public static string DecryptValue (string textToDecrypt);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string DecryptValue(string textToDecrypt) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.DecryptValue(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DecryptValue (textToDecrypt As String) As String" />
      <MemberSignature Language="F#" Value="static member DecryptValue : string -&gt; string" Usage="System.Fabric.Security.EncryptionUtility.DecryptValue textToDecrypt" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Deprecated DecryptText", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="textToDecrypt" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="textToDecrypt">
          <para>Der Zeichenfolgenwert zu entschlüsseln.</para>
        </param>
        <summary>
          <para>Entschlüsselt die Zeichenfolgenwerte, die durch Aufrufen von EncryptValue verschlüsselt wurden. Diese Methode ist veraltet. EncryptText-Methode sollte stattdessen verwendet werden.</para>
        </summary>
        <returns>
          <para>Der entschlüsselte Wert.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptText">
      <MemberSignature Language="C#" Value="public static string EncryptText (string textToEncrypt, string thumbprint, string storeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string EncryptText(string textToEncrypt, string thumbprint, string storeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.EncryptText(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EncryptText (textToEncrypt As String, thumbprint As String, storeName As String) As String" />
      <MemberSignature Language="F#" Value="static member EncryptText : string * string * string -&gt; string" Usage="System.Fabric.Security.EncryptionUtility.EncryptText (textToEncrypt, thumbprint, storeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="textToEncrypt" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="storeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="textToEncrypt">
          <para>Die Textzeichenfolge zu verschlüsseln.</para>
        </param>
        <param name="thumbprint">
          <para>Der Fingerabdruck des Verschlüsselungszertifikats.</para>
        </param>
        <param name="storeName">
          <para>Der Name des Zertifikatspeichers, aus denen Verschlüsselungsschlüssel Zertifikat abgerufen wird.</para>
        </param>
        <summary>
          <para>Verschlüsseln der Zeichenfolge mit einem installierten X509 Zertifikat. Zertifikatspeicherort LocalMachine und der Verschlüsselungsalgorithmus AES256 CBC.</para>
        </summary>
        <returns>
          <para>Der verschlüsselte Text als <see cref="T:System.String" />.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptText">
      <MemberSignature Language="C#" Value="public static string EncryptText (string textToEncrypt, string thumbprint, string storeName, System.Security.Cryptography.X509Certificates.StoreLocation storeLocation, string algorithmOid);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string EncryptText(string textToEncrypt, string thumbprint, string storeName, valuetype System.Security.Cryptography.X509Certificates.StoreLocation storeLocation, string algorithmOid) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.EncryptText(System.String,System.String,System.String,System.Security.Cryptography.X509Certificates.StoreLocation,System.String)" />
      <MemberSignature Language="F#" Value="static member EncryptText : string * string * string * System.Security.Cryptography.X509Certificates.StoreLocation * string -&gt; string" Usage="System.Fabric.Security.EncryptionUtility.EncryptText (textToEncrypt, thumbprint, storeName, storeLocation, algorithmOid)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="textToEncrypt" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="storeLocation" Type="System.Security.Cryptography.X509Certificates.StoreLocation" />
        <Parameter Name="algorithmOid" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="textToEncrypt">
          <para>Der Text verschlüsselt.</para>
        </param>
        <param name="thumbprint">
          <para>Der Fingerabdruck des Verschlüsselungszertifikats.</para>
        </param>
        <param name="storeName">
          <para>Der Name des Zertifikatspeichers, aus denen Verschlüsselungsschlüssel Zertifikat abgerufen wird.</para>
        </param>
        <param name="storeLocation">
          <para>Der Zertifikatsspeicher Speicherort zum Abrufen des Verschlüsselungszertifikats.</para>
        </param>
        <param name="algorithmOid">
          <para>Die Verschlüsselung Algorithmus Objekt-ID (OID).</para>
        </param>
        <summary>
          <para>Verschlüsseln der Zeichenfolge mit einem installierten X509 Zertifikat.</para>
        </summary>
        <returns>
          <para>Der verschlüsselte Text als <see cref="T:System.String" />.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptTextByCertFile">
      <MemberSignature Language="C#" Value="public static string EncryptTextByCertFile (string textToEncrypt, string certFileName, string algorithmOid);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string EncryptTextByCertFile(string textToEncrypt, string certFileName, string algorithmOid) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.EncryptTextByCertFile(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EncryptTextByCertFile (textToEncrypt As String, certFileName As String, algorithmOid As String) As String" />
      <MemberSignature Language="F#" Value="static member EncryptTextByCertFile : string * string * string -&gt; string" Usage="System.Fabric.Security.EncryptionUtility.EncryptTextByCertFile (textToEncrypt, certFileName, algorithmOid)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="textToEncrypt" Type="System.String" />
        <Parameter Name="certFileName" Type="System.String" />
        <Parameter Name="algorithmOid" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="textToEncrypt">
          <para>Der Text verschlüsselt.</para>
        </param>
        <param name="certFileName">
          <para>Der Dateipfad der Verschlüsselung-Zertifikat.</para>
        </param>
        <param name="algorithmOid">
          <para>Die Verschlüsselung Algorithmus Objekt-ID (OID).</para>
        </param>
        <summary>
          <para>Verschlüsseln der Zeichenfolge mit einem X509 Zertifikat in einer Datei.</para>
        </summary>
        <returns>
          <para>Der verschlüsselte Text als <see cref="T:System.String" />.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptValue">
      <MemberSignature Language="C#" Value="public static string EncryptValue (string thumbprint, string storeLocation, string textToEncrypt);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string EncryptValue(string thumbprint, string storeLocation, string textToEncrypt) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Security.EncryptionUtility.EncryptValue(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EncryptValue (thumbprint As String, storeLocation As String, textToEncrypt As String) As String" />
      <MemberSignature Language="F#" Value="static member EncryptValue : string * string * string -&gt; string" Usage="System.Fabric.Security.EncryptionUtility.EncryptValue (thumbprint, storeLocation, textToEncrypt)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Deprecated by EncryptText", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="storeLocation" Type="System.String" />
        <Parameter Name="textToEncrypt" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="thumbprint">
          <para>Der Fingerabdruck des Zertifikats verwendet, um Text zu verschlüsseln.</para>
        </param>
        <param name="storeLocation">
          <para>Die "StoreName" für das Zertifikat. Der Standardwert ist My-Zertifikatspeicher.</para>
        </param>
        <param name="textToEncrypt">
          <para>Der Textwert, der verschlüsselt werden muss.</para>
        </param>
        <summary>
          <para>String-Wert mit angegebenen Zertifikat verschlüsselt wird. Diese Methode ist veraltet. EncryptText-Methode sollte stattdessen verwendet werden.</para>
        </summary>
        <returns>
          <para>Der verschlüsselte Text als <see cref="T:System.String" />.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>