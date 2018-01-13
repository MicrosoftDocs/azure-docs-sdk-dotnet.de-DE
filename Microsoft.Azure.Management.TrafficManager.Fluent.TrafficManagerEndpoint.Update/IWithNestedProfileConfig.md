<Type Name="IWithNestedProfileConfig" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithNestedProfileConfig">
  <TypeSignature Language="C#" Value="public interface IWithNestedProfileConfig" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNestedProfileConfig" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithNestedProfileConfig" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNestedProfileConfig" />
  <TypeSignature Language="F#" Value="type IWithNestedProfileConfig = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase eines Endpunkts verschachtelten Profil aktualisieren ermöglicht Profil und minimale untergeordneten Endpunkts an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateNestedProfileEndpoint.IUpdateNestedProfileEndpoint ToProfile (Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile nestedProfile);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateNestedProfileEndpoint.IUpdateNestedProfileEndpoint ToProfile(class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile nestedProfile) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithNestedProfileConfig.ToProfile(Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToProfile (nestedProfile As ITrafficManagerProfile) As IUpdateNestedProfileEndpoint" />
      <MemberSignature Language="F#" Value="abstract member ToProfile : Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateNestedProfileEndpoint.IUpdateNestedProfileEndpoint" Usage="iWithNestedProfileConfig.ToProfile nestedProfile" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateNestedProfileEndpoint.IUpdateNestedProfileEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nestedProfile" Type="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile" />
      </Parameters>
      <Docs>
        <param name="nestedProfile">Die geschachtelte Traffic Manager-Profil.</param>
        <summary>
            Gibt eine geschachtelte Traffic Manager-Profil für den Endpunkt an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithMinimumEndpointsToEnableTraffic">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateNestedProfileEndpoint.IUpdateNestedProfileEndpoint WithMinimumEndpointsToEnableTraffic (int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateNestedProfileEndpoint.IUpdateNestedProfileEndpoint WithMinimumEndpointsToEnableTraffic(int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithNestedProfileConfig.WithMinimumEndpointsToEnableTraffic(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMinimumEndpointsToEnableTraffic (count As Integer) As IUpdateNestedProfileEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithMinimumEndpointsToEnableTraffic : int -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateNestedProfileEndpoint.IUpdateNestedProfileEndpoint" Usage="iWithNestedProfileConfig.WithMinimumEndpointsToEnableTraffic count" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateNestedProfileEndpoint.IUpdateNestedProfileEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="count">Die Anzahl der Endpunkte.</param>
        <summary>
            Gibt die minimale Anzahl von Endpunkten für online sein, damit die verschachtelten Profil fehlerfrei angesehen werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Updates für den Endpunkt.</return>
      </Docs>
    </Member>
  </Members>
</Type>