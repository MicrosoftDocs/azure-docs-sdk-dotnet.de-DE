<Type Name="IVirtualMachineSizesOperations" FullName="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSizesOperations">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineSizesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineSizesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSizesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineSizesOperations" />
  <TypeSignature Language="F#" Value="type IVirtualMachineSizesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            VirtualMachineSizesOperations-Vorgänge.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize&gt;&gt;&gt; ListWithHttpMessagesAsync (string location, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize&gt;&gt;&gt; ListWithHttpMessagesAsync(string location, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSizesOperations.ListWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize&gt;&gt;&gt;" Usage="iVirtualMachineSizesOperations.ListWithHttpMessagesAsync (location, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="location">
            Der Speicherort der virtual-Machine-Größen abgefragt wird.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet alle verfügbaren VM-Größen für ein Abonnement in einen Speicherort an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>