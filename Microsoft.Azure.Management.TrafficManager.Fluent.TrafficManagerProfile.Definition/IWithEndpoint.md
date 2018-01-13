<Type Name="IWithEndpoint" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint">
  <TypeSignature Language="C#" Value="public interface IWithEndpoint" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithEndpoint" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithEndpoint" />
  <TypeSignature Language="F#" Value="type IWithEndpoint = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Traffic Manager Profildefinition ermöglicht Endpunkt angegeben wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineAzureTargetEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IAzureTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt; DefineAzureTargetEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IAzureTargetEndpointBlank`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt; DefineAzureTargetEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint.DefineAzureTargetEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineAzureTargetEndpoint (name As String) As IAzureTargetEndpointBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineAzureTargetEndpoint : string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IAzureTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt;" Usage="iWithEndpoint.DefineAzureTargetEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IAzureTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name für den Endpunkt.</param>
        <summary>
            Gibt die Definition der Azure-Endpunkt an die Traffic Manager-Profil angefügt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die Phase, Konfiguration für den Endpunkt darstellt.</return>
      </Docs>
    </Member>
    <Member MemberName="DefineExternalTargetEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IExternalTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt; DefineExternalTargetEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IExternalTargetEndpointBlank`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt; DefineExternalTargetEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint.DefineExternalTargetEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineExternalTargetEndpoint (name As String) As IExternalTargetEndpointBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineExternalTargetEndpoint : string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IExternalTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt;" Usage="iWithEndpoint.DefineExternalTargetEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IExternalTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name für den Endpunkt.</param>
        <summary>
            Gibt die Definition einen externen Endpunkt an die Traffic Manager-Profil angefügt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die Phase, Konfiguration für den Endpunkt darstellt.</return>
      </Docs>
    </Member>
    <Member MemberName="DefineNestedTargetEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.INestedProfileTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt; DefineNestedTargetEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.INestedProfileTargetEndpointBlank`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt; DefineNestedTargetEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint.DefineNestedTargetEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNestedTargetEndpoint (name As String) As INestedProfileTargetEndpointBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineNestedTargetEndpoint : string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.INestedProfileTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt;" Usage="iWithEndpoint.DefineNestedTargetEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.INestedProfileTargetEndpointBlank&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name für den Endpunkt.</param>
        <summary>
            Gibt die Definition eines Endpunkts verschachtelten Profil an die Traffic Manager-Profil angefügt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die Phase, Konfiguration für den Endpunkt darstellt.</return>
      </Docs>
    </Member>
  </Members>
</Type>