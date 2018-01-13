<Type Name="TableColumnAttribute" FullName="Microsoft.Azure.Mobile.Server.Tables.TableColumnAttribute">
  <TypeSignature Language="C#" Value="public sealed class TableColumnAttribute : Attribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TableColumnAttribute extends System.Attribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Tables.TableColumnAttribute" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TableColumnAttribute&#xA;Inherits Attribute" />
  <TypeSignature Language="F#" Value="type TableColumnAttribute = class&#xA;    inherit Attribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Attribute</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.AttributeUsage(System.AttributeTargets.Property | System.AttributeTargets.Field, AllowMultiple=false, Inherited=true)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Die <see cref="T:Microsoft.Azure.Mobile.Server.Tables.TableColumnAttribute" /> können verwendet werden, um datenmodelleigenschaften mit einer Anmerkung versehen, die von verwendete Systemeigenschaften darstellen der <see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />. Durch, der angibt, welche Spalten sind die Id, Version, CreatedAt, Spalten usw., können die verschiedenen Domänenmanager diese Informationen zum Bereitstellen der besten möglichen Zuordnung bestimmten Back-End-Speicher nutzen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableColumnAttribute (Microsoft.Azure.Mobile.Server.Tables.TableColumnType columnType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Mobile.Server.Tables.TableColumnType columnType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.TableColumnAttribute.#ctor(Microsoft.Azure.Mobile.Server.Tables.TableColumnType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (columnType As TableColumnType)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.Tables.TableColumnAttribute : Microsoft.Azure.Mobile.Server.Tables.TableColumnType -&gt; Microsoft.Azure.Mobile.Server.Tables.TableColumnAttribute" Usage="new Microsoft.Azure.Mobile.Server.Tables.TableColumnAttribute columnType" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="columnType" Type="Microsoft.Azure.Mobile.Server.Tables.TableColumnType" />
      </Parameters>
      <Docs>
        <param name="columnType">Die <see cref="T:Microsoft.Azure.Mobile.Server.Tables.TableColumnType" /> für die Eigenschaft wird auf dieses Attribut angewendet.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Mobile.Server.Tables.TableColumnAttribute" /> mit einem bestimmten <paramref name="columnType" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ColumnType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Mobile.Server.Tables.TableColumnType ColumnType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Mobile.Server.Tables.TableColumnType ColumnType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Tables.TableColumnAttribute.ColumnType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ColumnType As TableColumnType" />
      <MemberSignature Language="F#" Value="member this.ColumnType : Microsoft.Azure.Mobile.Server.Tables.TableColumnType" Usage="Microsoft.Azure.Mobile.Server.Tables.TableColumnAttribute.ColumnType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.Tables.TableColumnType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die <see cref="T:Microsoft.Azure.Mobile.Server.Tables.TableColumnType" /> für die Eigenschaft wird auf dieses Attribut angewendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TableColumnAnnotation">
      <MemberSignature Language="C#" Value="public static string TableColumnAnnotation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string TableColumnAnnotation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Tables.TableColumnAttribute.TableColumnAnnotation" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property TableColumnAnnotation As String" />
      <MemberSignature Language="F#" Value="member this.TableColumnAnnotation : string" Usage="Microsoft.Azure.Mobile.Server.Tables.TableColumnAttribute.TableColumnAnnotation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Beim Registrieren der <see cref="T:Microsoft.Azure.Mobile.Server.Tables.TableColumnAttribute" /> mit Entity Framework eine Modell-Generator Code erste Konvention verwendet, verwenden Sie diesen Namen als Tabellennamen Spalte Anmerkung. Finden Sie unter <c>https://entityframework.codeplex.com/wikipage?title=Code%20First%20Annotations</c> Weitere Informationen zu Entity Framework code first-Konventionen und Code Anmerkungen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>