<Type Name="TableMobileAppOptionsExtensions" FullName="Microsoft.Azure.Mobile.Server.Config.TableMobileAppOptionsExtensions">
  <TypeSignature Language="C#" Value="public static class TableMobileAppOptionsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TableMobileAppOptionsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Config.TableMobileAppOptionsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TableMobileAppOptionsExtensions" />
  <TypeSignature Language="F#" Value="type TableMobileAppOptionsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Erweiterungsmethoden für <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" />.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddTables">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration AddTables (this Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration config);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration AddTables(class Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration config) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.TableMobileAppOptionsExtensions.AddTables(Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function AddTables (config As MobileAppConfiguration) As MobileAppConfiguration" />
      <MemberSignature Language="F#" Value="static member AddTables : Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration -&gt; Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" Usage="Microsoft.Azure.Mobile.Server.Config.TableMobileAppOptionsExtensions.AddTables config" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="config" Type="Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" RefType="this" />
      </Parameters>
      <Docs>
        <param name="config">Konfigurationsobjekt.</param>
        <summary>
            Registriert ein neues <see cref="T:Microsoft.Azure.Mobile.Server.Tables.Config.MobileAppTableConfiguration" /> ordnet eine Route für alle Domänencontroller, auf denen Ableitung <see cref="T:Microsoft.Azure.Mobile.Server.Tables.TableController" />.
            </summary>
        <returns>Der aktuelle <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddTables">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration AddTables (this Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration config, Microsoft.Azure.Mobile.Server.Tables.Config.MobileAppTableConfiguration tableConfig);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration AddTables(class Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration config, class Microsoft.Azure.Mobile.Server.Tables.Config.MobileAppTableConfiguration tableConfig) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.TableMobileAppOptionsExtensions.AddTables(Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration,Microsoft.Azure.Mobile.Server.Tables.Config.MobileAppTableConfiguration)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function AddTables (config As MobileAppConfiguration, tableConfig As MobileAppTableConfiguration) As MobileAppConfiguration" />
      <MemberSignature Language="F#" Value="static member AddTables : Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration * Microsoft.Azure.Mobile.Server.Tables.Config.MobileAppTableConfiguration -&gt; Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" Usage="Microsoft.Azure.Mobile.Server.Config.TableMobileAppOptionsExtensions.AddTables (config, tableConfig)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="We only want this extension to apply to MobileAppConfiguration, not just any AppConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="config" Type="Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" RefType="this" />
        <Parameter Name="tableConfig" Type="Microsoft.Azure.Mobile.Server.Tables.Config.MobileAppTableConfiguration" />
      </Parameters>
      <Docs>
        <param name="config">Konfigurationsobjekt.</param>
        <param name="tableConfig"></param>
        <summary>
            Registriert das angegebene <see cref="T:Microsoft.Azure.Mobile.Server.Tables.Config.MobileAppTableConfiguration" />.
            </summary>
        <returns>Der aktuelle <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithTableControllerConfigProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration WithTableControllerConfigProvider (this Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration options, Microsoft.Azure.Mobile.Server.Tables.ITableControllerConfigProvider tableConfigProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration WithTableControllerConfigProvider(class Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration options, class Microsoft.Azure.Mobile.Server.Tables.ITableControllerConfigProvider tableConfigProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.TableMobileAppOptionsExtensions.WithTableControllerConfigProvider(Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration,Microsoft.Azure.Mobile.Server.Tables.ITableControllerConfigProvider)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function WithTableControllerConfigProvider (options As MobileAppConfiguration, tableConfigProvider As ITableControllerConfigProvider) As MobileAppConfiguration" />
      <MemberSignature Language="F#" Value="static member WithTableControllerConfigProvider : Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration * Microsoft.Azure.Mobile.Server.Tables.ITableControllerConfigProvider -&gt; Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" Usage="Microsoft.Azure.Mobile.Server.Config.TableMobileAppOptionsExtensions.WithTableControllerConfigProvider (options, tableConfigProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="We only want this extension to apply to MobileAppConfiguration, not just any AppConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" RefType="this" />
        <Parameter Name="tableConfigProvider" Type="Microsoft.Azure.Mobile.Server.Tables.ITableControllerConfigProvider" />
      </Parameters>
      <Docs>
        <param name="options">Konfigurationsobjekt.</param>
        <param name="tableConfigProvider">Der Anbieter zu registrieren.</param>
        <summary>
            Registriert das angegebene <see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableControllerConfigProvider" /> mit der <see cref="T:System.Web.Http.HttpConfiguration" />.
            Hiermit können Sie das Überschreiben der standardmäßigen <see cref="T:Microsoft.Azure.Mobile.Server.Tables.TableController" /> Konfiguration.
            </summary>
        <returns>Der aktuelle <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>