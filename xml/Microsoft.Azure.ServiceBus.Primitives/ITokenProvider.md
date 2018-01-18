<Type Name="ITokenProvider" FullName="Microsoft.Azure.ServiceBus.Primitives.ITokenProvider">
  <TypeSignature Language="C#" Value="public interface ITokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITokenProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Primitives.ITokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITokenProvider" />
  <TypeSignature Language="F#" Value="type ITokenProvider = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d20e1-101">Stellt einen Tokenanbieter Interface Definition bereit.</span><span class="sxs-lookup"><span data-stu-id="d20e1-101">Provides interface definition of a token provider.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Primitives.SecurityToken&gt; GetTokenAsync (string appliesTo, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Primitives.SecurityToken&gt; GetTokenAsync(string appliesTo, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.ITokenProvider.GetTokenAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTokenAsync (appliesTo As String, timeout As TimeSpan) As Task(Of SecurityToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTokenAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Primitives.SecurityToken&gt;" Usage="iTokenProvider.GetTokenAsync (appliesTo, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Primitives.SecurityToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="appliesTo"><span data-ttu-id="d20e1-102">Der URI, der das Zugriffstoken gilt.</span><span class="sxs-lookup"><span data-stu-id="d20e1-102">The URI which the access token applies to</span></span></param>
        <param name="timeout"><span data-ttu-id="d20e1-103">Die Zeitspanne an, die angibt, den Timeoutwert für die Nachricht abruft, die das Sicherheitstoken</span><span class="sxs-lookup"><span data-stu-id="d20e1-103">The time span that specifies the timeout value for the message that gets the security token</span></span></param>
        <summary>
            <span data-ttu-id="d20e1-104">Ruft eine <see cref="T:Microsoft.Azure.ServiceBus.Primitives.SecurityToken" /> ab.</span><span class="sxs-lookup"><span data-stu-id="d20e1-104">Gets a <see cref="T:Microsoft.Azure.ServiceBus.Primitives.SecurityToken" />.</span></span>
            </summary>
        <returns>
          <see cref="T:Microsoft.Azure.ServiceBus.Primitives.SecurityToken" />
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>