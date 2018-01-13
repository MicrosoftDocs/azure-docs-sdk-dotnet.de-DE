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
            Stellt das Ergebnis eines tabellenvorgangs dar.
            </summary>
    <remarks>Die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResult" /> -Klasse kapselt die HTTP-Antwort und alle Entitäten zurückgegeben, die für einen bestimmten <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" />.</remarks>
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
            Ruft ab oder legt das ETag zurückgegeben, mit der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> -anforderungsergebnisses.
            </summary>
        <value>Das ETag zurückgegeben, mit der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> -anforderungsergebnisses.</value>
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
            Ruft ab oder legt den HTTP-Statuscode zurückgegebenes eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> Anforderung.
            </summary>
        <value>Der HTTP-Statuscode zurückgegeben werden, indem eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> Anforderung.</value>
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
            Ruft ab oder legt das zurückgegebene Ergebnis der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" /> als ein <see cref="T:System.Object" />.
            </summary>
        <value>Das Ergebnis des tabellenvorgangs als ein <see cref="T:System.Object" />.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>