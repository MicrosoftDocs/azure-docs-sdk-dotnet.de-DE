<Type Name="TableServiceExtensions" FullName="Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceExtensions">
  <TypeSignature Language="C#" Value="public static class TableServiceExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TableServiceExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TableServiceExtensions" />
  <TypeSignature Language="F#" Value="type TableServiceExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Stellt einen Satz von Erweiterungen für den Tabellendienst bereit.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AsTableServiceQuery&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery&lt;TElement&gt; AsTableServiceQuery&lt;TElement&gt; (this System.Linq.IQueryable&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1&lt;!!TElement&gt; AsTableServiceQuery&lt;TElement&gt;(class System.Linq.IQueryable`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceExtensions.AsTableServiceQuery``1(System.Linq.IQueryable{``0},Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function AsTableServiceQuery(Of TElement) (query As IQueryable(Of TElement), context As TableServiceContext) As TableServiceQuery(Of TElement)" />
      <MemberSignature Language="F#" Value="static member AsTableServiceQuery : System.Linq.IQueryable&lt;'Element&gt; * Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext -&gt; Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery&lt;'Element&gt;" Usage="Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceExtensions.AsTableServiceQuery (query, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="System.Linq.IQueryable&lt;TElement&gt;" RefType="this" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Der Typ des Elements.</typeparam>
        <param name="query">Die Abfrage.</param>
        <param name="context">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" /> Objekt, das den Laufzeitkontext des tabellendiensts darstellt.</param>
        <summary>
            Konvertiert die Abfrage in einem <see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1" /> -Objekt, das zusätzliche Vorgänge wie Wiederholungen unterstützt.
            </summary>
        <returns>Die konvertierte Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>