<Type Name="TableHttpWebResponseParsers" FullName="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebResponseParsers">
  <TypeSignature Language="C#" Value="public static class TableHttpWebResponseParsers" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TableHttpWebResponseParsers extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebResponseParsers" />
  <TypeSignature Language="VB.NET" Value="Public Class TableHttpWebResponseParsers" />
  <TypeSignature Language="F#" Value="type TableHttpWebResponseParsers = class" />
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
            Stellt einen Satz von Methoden zum Analysieren eines Antwortstream vom Tabellendienst bereit.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetRequestId">
      <MemberSignature Language="C#" Value="public static string GetRequestId (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetRequestId(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebResponseParsers.GetRequestId(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetRequestId (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetRequestId : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebResponseParsers.GetRequestId response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response">Die Webantwort.</param>
        <summary>
            Ruft die Anforderungs-ID aus der Antwort ab.
            </summary>
        <returns>Ein eindeutiger Wert, der der Anforderung zugeordnet ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadServiceProperties">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties ReadServiceProperties (System.IO.Stream inputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties ReadServiceProperties(class System.IO.Stream inputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebResponseParsers.ReadServiceProperties(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadServiceProperties (inputStream As Stream) As ServiceProperties" />
      <MemberSignature Language="F#" Value="static member ReadServiceProperties : System.IO.Stream -&gt; Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebResponseParsers.ReadServiceProperties inputStream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="inputStream">Der Stream, aus dem die Diensteigenschaften gelesen werden soll.</param>
        <summary>
            Liest die Diensteigenschaften aus einem Stream.
            </summary>
        <returns>Die Diensteigenschaften, die im Stream gespeichert.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadServiceStats">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Storage.Shared.Protocol.ServiceStats ReadServiceStats (System.IO.Stream inputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Storage.Shared.Protocol.ServiceStats ReadServiceStats(class System.IO.Stream inputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebResponseParsers.ReadServiceStats(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadServiceStats (inputStream As Stream) As ServiceStats" />
      <MemberSignature Language="F#" Value="static member ReadServiceStats : System.IO.Stream -&gt; Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebResponseParsers.ReadServiceStats inputStream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.Shared.Protocol.ServiceStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="inputStream">Der Stream, aus dem die dienststatistik gelesen werden soll.</param>
        <summary>
            Liest dienststatistik aus einem Stream.
            </summary>
        <returns>Die dienststatistik im Stream gespeichert.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadSharedAccessIdentifiers">
      <MemberSignature Language="C#" Value="public static void ReadSharedAccessIdentifiers (System.IO.Stream inputStream, Microsoft.Azure.CosmosDB.Table.TablePermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ReadSharedAccessIdentifiers(class System.IO.Stream inputStream, class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebResponseParsers.ReadSharedAccessIdentifiers(System.IO.Stream,Microsoft.Azure.CosmosDB.Table.TablePermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ReadSharedAccessIdentifiers (inputStream As Stream, permissions As TablePermissions)" />
      <MemberSignature Language="F#" Value="static member ReadSharedAccessIdentifiers : System.IO.Stream * Microsoft.Azure.CosmosDB.Table.TablePermissions -&gt; unit" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebResponseParsers.ReadSharedAccessIdentifiers (inputStream, permissions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inputStream" Type="System.IO.Stream" />
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
      </Parameters>
      <Docs>
        <param name="inputStream">Der Datenstrom des XML-Richtlinien.</param>
        <param name="permissions">Das Berechtigungen-Objekt, das auf dem die Richtlinien, die zu schreibenden sind.</param>
        <summary>
            Liest die Zugriffsrichtlinien für die Freigabe aus einem Datenstrom im XML-Format an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>