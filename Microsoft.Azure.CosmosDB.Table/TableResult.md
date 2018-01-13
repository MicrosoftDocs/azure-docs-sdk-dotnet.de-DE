<Type Name="TableResult" FullName="Microsoft.Azure.CosmosDB.Table.TableResult">
  <TypeSignature Language="C#" Value="public sealed class TableResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TableResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.TableResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TableResult" />
  <TypeSignature Language="F#" Value="type TableResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt das Ergebnis eines tabellenvorgangs dar.
            </summary>
    <remarks>Die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> -Klasse kapselt die HTTP-Antwort und alle Entitäten zurückgegeben, die für einen bestimmten <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableResult.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableResult.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das ETag zurückgegeben, mit der <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> -anforderungsergebnisses.
            </summary>
        <value>Das ETag zurückgegeben, mit der <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> -anforderungsergebnisses.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpStatusCode">
      <MemberSignature Language="C#" Value="public int HttpStatusCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 HttpStatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableResult.HttpStatusCode" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpStatusCode As Integer" />
      <MemberSignature Language="F#" Value="member this.HttpStatusCode : int with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableResult.HttpStatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den HTTP-Statuscode zurückgegebenes eine <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> Anforderung.
            </summary>
        <value>Der HTTP-Statuscode zurückgegeben werden, indem eine <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> Anforderung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public object Result { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableResult.Result" />
      <MemberSignature Language="VB.NET" Value="Public Property Result As Object" />
      <MemberSignature Language="F#" Value="member this.Result : obj with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableResult.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das zurückgegebene Ergebnis der <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> als ein <see cref="T:System.Object" />.
            </summary>
        <value>Das Ergebnis des tabellenvorgangs als ein <see cref="T:System.Object" />.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionToken">
      <MemberSignature Language="C#" Value="public string SessionToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableResult.SessionToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SessionToken As String" />
      <MemberSignature Language="F#" Value="member this.SessionToken : string" Usage="Microsoft.Azure.CosmosDB.Table.TableResult.SessionToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Sitzungstoken zurückgegeben, aus der <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> -anforderungsergebnisses.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>