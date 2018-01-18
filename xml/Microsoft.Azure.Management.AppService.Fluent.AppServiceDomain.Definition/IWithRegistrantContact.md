<Type Name="IWithRegistrantContact" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithRegistrantContact">
  <TypeSignature Language="C#" Value="public interface IWithRegistrantContact" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRegistrantContact" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithRegistrantContact" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRegistrantContact" />
  <TypeSignature Language="F#" Value="type IWithRegistrantContact = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a4710-101">Die Domänendefinition einer ermöglicht Registrant Kontakt festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="a4710-101">A domain definition allowing registrant contact to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineRegistrantContact">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate&gt; DefineRegistrantContact ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IBlank`1&lt;class Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate&gt; DefineRegistrantContact() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithRegistrantContact.DefineRegistrantContact" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineRegistrantContact () As IBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineRegistrantContact : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate&gt;" Usage="iWithRegistrantContact.DefineRegistrantContact " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a4710-102">Startet die Definition eines neuen Kontakts für die Domäne an.</span><span class="sxs-lookup"><span data-stu-id="a4710-102">Starts the definition of a new domain contact.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a4710-103">Die erste Phase der Domäne, wenden Sie sich an die Definition.</span><span class="sxs-lookup"><span data-stu-id="a4710-103">The first stage of the domain contact definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithRegistrantContact">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate WithRegistrantContact (Microsoft.Azure.Management.AppService.Fluent.Models.Contact contact);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate WithRegistrantContact(class Microsoft.Azure.Management.AppService.Fluent.Models.Contact contact) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithRegistrantContact.WithRegistrantContact(Microsoft.Azure.Management.AppService.Fluent.Models.Contact)" />
      <MemberSignature Language="F#" Value="abstract member WithRegistrantContact : Microsoft.Azure.Management.AppService.Fluent.Models.Contact -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate" Usage="iWithRegistrantContact.WithRegistrantContact contact" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="contact" Type="Microsoft.Azure.Management.AppService.Fluent.Models.Contact" />
      </Parameters>
      <Docs>
        <param name="contact"><span data-ttu-id="a4710-104">Wenden Sie sich Registrant an.</span><span class="sxs-lookup"><span data-stu-id="a4710-104">The registrant contact.</span></span></param>
        <summary>
            <span data-ttu-id="a4710-105">Geben Sie den Kontakt Registrant.</span><span class="sxs-lookup"><span data-stu-id="a4710-105">Specify the registrant contact.</span></span> <span data-ttu-id="a4710-106">Standardmäßig ist dies auch den Kontakt für den Administrator, der Abrechnung und an den technischen.</span><span class="sxs-lookup"><span data-stu-id="a4710-106">By default, this is also the contact for admin, billing, and tech.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a4710-107">die nächste Phase der Domänendefinition.</span><span class="sxs-lookup"><span data-stu-id="a4710-107">The next stage of domain definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>