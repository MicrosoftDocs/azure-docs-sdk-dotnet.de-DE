<Type Name="ActivityTypeOperations" FullName="Microsoft.Azure.Management.DataFactories.ActivityTypeOperations">
  <TypeSignature Language="C#" Value="public class ActivityTypeOperations : Hyak.Common.IServiceOperations&lt;Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient&gt;, Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActivityTypeOperations extends System.Object implements class Hyak.Common.IServiceOperations`1&lt;class Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient&gt;, class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations" />
  <TypeSignature Language="VB.NET" Value="Public Class ActivityTypeOperations&#xA;Implements IActivityTypeOperations, IServiceOperations(Of DataFactoryManagementClient)" />
  <TypeSignature Language="F#" Value="type ActivityTypeOperations = class&#xA;    interface IServiceOperations&lt;DataFactoryManagementClient&gt;&#xA;    interface IActivityTypeOperations" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Hyak.Common.IServiceOperations&lt;Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.DataFactories.IActivityTypeOperations</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Vorgänge zum Verwalten von Data Factory "activitytypes".
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (string resourceGroupName, string dataFactoryName, string activityTypeName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(string resourceGroupName, string dataFactoryName, string activityTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.BeginDeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;&#xA;override this.BeginDeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="activityTypeOperations.BeginDeleteAsync (resourceGroupName, dataFactoryName, activityTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.BeginDeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.ActivityTypeOperations/&lt;BeginDeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Erforderlich. Der Ressourcengruppenname der Data Factory.
            </param>
        <param name="dataFactoryName">
            Erforderlich. Der Name der Data Factory.
            </param>
        <param name="activityTypeName">
            Erforderlich. Der Name des der ActivityType.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Löschen einer ActivityType-Instanz.
            </summary>
        <returns>
            Eine standarddienstantwort für lang ausgeführte Vorgänge.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Client">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient Client { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient Client" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.Client" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Client As DataFactoryManagementClient" />
      <MemberSignature Language="F#" Value="member this.Client : Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.Client" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;&#xA;override this.CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;" Usage="activityTypeOperations.CreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.ActivityTypeOperations/&lt;CreateOrUpdateAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Erforderlich. Der Ressourcengruppenname der Data Factory.
            </param>
        <param name="dataFactoryName">
            Erforderlich. Der Name der Data Factory.
            </param>
        <param name="parameters">
            Erforderlich. Die Parameter zum Erstellen oder Aktualisieren einer ActivityType-Definition erforderlich.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Erstellen Sie oder aktualisieren Sie einer ActivityType.
            </summary>
        <returns>
            Erstellen oder aktualisieren ActivityType Antworten für den Vorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string activityTypeName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string activityTypeName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.CreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;&#xA;override this.CreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;" Usage="activityTypeOperations.CreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, activityTypeName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.CreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.ActivityTypeOperations/&lt;CreateOrUpdateWithRawJsonContentAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Erforderlich. Der Ressourcengruppenname der Data Factory.
            </param>
        <param name="dataFactoryName">
            Erforderlich. Der Name der Data Factory.
            </param>
        <param name="activityTypeName">
            Erforderlich. Der Name einer ActivityType.
            </param>
        <param name="parameters">
            Erforderlich. Die Parameter zum Erstellen oder Aktualisieren einer ActivityType-Definition erforderlich.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Erstellen Sie oder aktualisieren Sie einer ActivityType.
            </summary>
        <returns>
            Erstellen oder aktualisieren ActivityType Antworten für den Vorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (string resourceGroupName, string dataFactoryName, string activityTypeName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(string resourceGroupName, string dataFactoryName, string activityTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;&#xA;override this.DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="activityTypeOperations.DeleteAsync (resourceGroupName, dataFactoryName, activityTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.ActivityTypeOperations/&lt;DeleteAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Erforderlich. Der Ressourcengruppenname der Data Factory.
            </param>
        <param name="dataFactoryName">
            Erforderlich. Der Name der Data Factory.
            </param>
        <param name="activityTypeName">
            Erforderlich. Der Name des der ActivityType.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Löschen einer ActivityType-Instanz.
            </summary>
        <returns>
            Eine standarddienstantwort für lang ausgeführte Vorgänge.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.GetAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt;&#xA;override this.GetAsync : string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt;" Usage="activityTypeOperations.GetAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.GetAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.ActivityTypeOperations/&lt;GetAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Erforderlich. Der Ressourcengruppenname der Data Factory.
            </param>
        <param name="dataFactoryName">
            Erforderlich. Der Name der Data Factory.
            </param>
        <param name="parameters">
            Erforderlich. Parameter, die zum Abrufen einer ActivityType-Definition angibt.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft eine ActivityType-Instanz ab.
            </summary>
        <returns>
            Die ActivityType Get Operation-Antwort.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;&#xA;override this.ListAsync : string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;" Usage="activityTypeOperations.ListAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.ActivityTypeOperations/&lt;ListAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Erforderlich. Der Ressourcengruppenname der Data Factory.
            </param>
        <param name="dataFactoryName">
            Erforderlich. Der Name der Data Factory.
            </param>
        <param name="parameters">
            Erforderlich. Parameter, die angibt, wie eine Liste der ActivityType-Definitionen zurückzugeben.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft die erste Seite der ActivityType-Instanzen mit dem Link zur nächsten Seite ab.
            </summary>
        <returns>
            Die Liste ActivityType Operation-Antwort.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;&#xA;override this.ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;" Usage="activityTypeOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.ListNextAsync(System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.ActivityTypeOperations/&lt;ListNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            Erforderlich. Die Url zur nächsten Seite "activitytypes".
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft die nächste Seite der ActivityType-Instanzen mit dem Link zur nächsten Seite ab.
            </summary>
        <returns>
            Die Liste ActivityType Operation-Antwort.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>