<Type Name="TableResult" FullName="Microsoft.WindowsAzure.Storage.Table.TableResult">
  <TypeSignature Language="C#" Value="public sealed class TableResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TableResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.TableResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TableResult" />
  <TypeSignature Language="F#" Value="type TableResult = class" />
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
            <span data-ttu-id="20deb-101">Stellt das Ergebnis eines tabellenvorgangs dar.</span><span class="sxs-lookup"><span data-stu-id="20deb-101">Represents the result of a table operation.</span></span>
            </summary>
    <remarks><span data-ttu-id="20deb-102">Die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResult" /> -Klasse kapselt die HTTP-Antwort und alle Entitäten zurückgegeben, die für einen bestimmten <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" />.</span><span class="sxs-lookup"><span data-stu-id="20deb-102">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResult" /> class encapsulates the HTTP response and any entities returned for a particular <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" />.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableResult.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableResult.Etag" />
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
            <span data-ttu-id="20deb-103">Ruft ab oder legt das ETag zurückgegeben, mit der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> -anforderungsergebnisses.</span><span class="sxs-lookup"><span data-stu-id="20deb-103">Gets or sets the ETag returned with the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> request results.</span></span>
            </summary>
        <value><span data-ttu-id="20deb-104">Das ETag zurückgegeben, mit der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> -anforderungsergebnisses.</span><span class="sxs-lookup"><span data-stu-id="20deb-104">The ETag returned with the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> request results.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpStatusCode">
      <MemberSignature Language="C#" Value="public int HttpStatusCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 HttpStatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableResult.HttpStatusCode" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpStatusCode As Integer" />
      <MemberSignature Language="F#" Value="member this.HttpStatusCode : int with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableResult.HttpStatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20deb-105">Ruft ab oder legt den HTTP-Statuscode zurückgegebenes eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> Anforderung.</span><span class="sxs-lookup"><span data-stu-id="20deb-105">Gets or sets the HTTP status code returned by a <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> request.</span></span>
            </summary>
        <value><span data-ttu-id="20deb-106">Der HTTP-Statuscode zurückgegeben werden, indem eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> Anforderung.</span><span class="sxs-lookup"><span data-stu-id="20deb-106">The HTTP status code returned by a <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> request.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public object Result { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableResult.Result" />
      <MemberSignature Language="VB.NET" Value="Public Property Result As Object" />
      <MemberSignature Language="F#" Value="member this.Result : obj with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableResult.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20deb-107">Ruft ab oder legt das zurückgegebene Ergebnis der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> als ein <see cref="T:System.Object" />.</span><span class="sxs-lookup"><span data-stu-id="20deb-107">Gets or sets the result returned by the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> as an <see cref="T:System.Object" />.</span></span>
            </summary>
        <value><span data-ttu-id="20deb-108">Das Ergebnis des tabellenvorgangs als ein <see cref="T:System.Object" />.</span><span class="sxs-lookup"><span data-stu-id="20deb-108">The result of the table operation as an <see cref="T:System.Object" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>