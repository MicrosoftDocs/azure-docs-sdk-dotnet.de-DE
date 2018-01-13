<Type Name="AdlsFileNotFoundException" FullName="Microsoft.Azure.Management.DataLake.Store.Models.AdlsFileNotFoundException">
  <TypeSignature Language="C#" Value="public class AdlsFileNotFoundException : Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdlsFileNotFoundException extends Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsFileNotFoundException" />
  <TypeSignature Language="VB.NET" Value="Public Class AdlsFileNotFoundException&#xA;Inherits AdlsRemoteException" />
  <TypeSignature Language="F#" Value="type AdlsFileNotFoundException = class&#xA;    inherit AdlsRemoteException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("FileNotFoundException")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="2a49d-101">Eine WebHDFS-Ausnahme ausgelöst, der angibt, die Datei oder Ordner konnte nicht gefunden werden.</span><span class="sxs-lookup"><span data-stu-id="2a49d-101">A WebHDFS exception thrown indicating the file or folder could not be found.</span></span> <span data-ttu-id="2a49d-102">Wird ausgelöst, wenn ein Antwortcode Fehler 404 (nicht gefunden) zurückgegeben wird.</span><span class="sxs-lookup"><span data-stu-id="2a49d-102">Thrown when a 404 error response code is returned (not found).</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdlsFileNotFoundException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.AdlsFileNotFoundException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2a49d-103">Initialisiert eine neue Instanz der AdlsFileNotFoundException-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2a49d-103">Initializes a new instance of the AdlsFileNotFoundException class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdlsFileNotFoundException (string javaClassName = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string javaClassName, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.AdlsFileNotFoundException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional javaClassName As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.AdlsFileNotFoundException : string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.AdlsFileNotFoundException" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.AdlsFileNotFoundException (javaClassName, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="javaClassName" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="javaClassName"><span data-ttu-id="2a49d-104">Das vollständige Paket Klassenname für die Ausnahme ausgelöst wird, z. B. "java.lang.IllegalArgumentException".</span><span class="sxs-lookup"><span data-stu-id="2a49d-104">the full class package name for the exception thrown, such as 'java.lang.IllegalArgumentException'.</span></span></param>
        <param name="message"><span data-ttu-id="2a49d-105">die die ausgelöste Ausnahme, z. B. zugeordnete Meldung ' Ungültiger Wert für Webhdfs-Parameter "Berechtigung":... ".</span><span class="sxs-lookup"><span data-stu-id="2a49d-105">the message associated with the exception that was thrown, such as 'Invalid value for webhdfs parameter "permission":...'.</span></span></param>
        <summary>
            <span data-ttu-id="2a49d-106">Initialisiert eine neue Instanz der AdlsFileNotFoundException-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2a49d-106">Initializes a new instance of the AdlsFileNotFoundException class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>