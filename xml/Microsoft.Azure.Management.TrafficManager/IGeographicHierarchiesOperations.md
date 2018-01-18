<Type Name="IGeographicHierarchiesOperations" FullName="Microsoft.Azure.Management.TrafficManager.IGeographicHierarchiesOperations">
  <TypeSignature Language="C#" Value="public interface IGeographicHierarchiesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IGeographicHierarchiesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.IGeographicHierarchiesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IGeographicHierarchiesOperations" />
  <TypeSignature Language="F#" Value="type IGeographicHierarchiesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="53668-101">GeographicHierarchiesOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="53668-101">GeographicHierarchiesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetDefaultWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerGeographicHierarchy&gt;&gt; GetDefaultWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerGeographicHierarchy&gt;&gt; GetDefaultWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.IGeographicHierarchiesOperations.GetDefaultWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDefaultWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerGeographicHierarchy&gt;&gt;" Usage="iGeographicHierarchiesOperations.GetDefaultWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerGeographicHierarchy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="53668-102">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="53668-102">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="53668-103">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="53668-103">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="53668-104">Ruft die standardmäßige geografische Hierarchie, die von der geografischen datenverkehrrouting-Methode verwendet.</span><span class="sxs-lookup"><span data-stu-id="53668-104">Gets the default Geographic Hierarchy used by the Geographic traffic routing method.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="53668-105">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="53668-105">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="53668-106">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="53668-106">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="53668-107">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="53668-107">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>